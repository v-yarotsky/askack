AskAck.vim
=========

An addition to [ack.vim](https://github.com/mileszs/ack.vim), allows interactive search-in-project, remembers previous search.
The plugin is compatible with [Pathogen](https://github.com/tpope/vim-pathogen).

suggested mappings:

    " <C-/> - show search prompt
    nmap  :ACK<CR>
    " <C-/> on visual selection - search selected text in project
    vnoremap  "hy:Ack <C-r>h<CR>

