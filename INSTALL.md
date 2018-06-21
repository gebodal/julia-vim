# Installation instructions

### Using [vundle]

Add a new plugin line to your `.vimrc`:

``` vim
Plugin 'JuliaEditorSupport/julia-vim'
```

Run `vim` and update your bundles:

``` vim
:PluginInstall!
```

### Manually

Copy (or symlink) the contents of this repository into the vim application support directory:

``` bash
git clone git://github.com/JuliaEditorSupport/julia-vim.git
cd julia-vim
mkdir -p ~/.vim
cp -R * ~/.vim
```
