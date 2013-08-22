% Vim Tip: arrow keys
% Hugo Roy
% 2013-06-20 14:13:00

# Make arrows behave in VIM like in a GUI text editor

This is wholly heretic to VIM purists, but I find it very useful
for people who do use ↑ and ↓ keys and do not intend to use them
as a replacement for k and j. Just add in your <a
href="https://github.com/hugoroy/.vim/blob/master/vimrc">~/.vimrc</a>:

<script src="https://gist.github.com/hugoroy/5822226.js"></script>
<noscript><pre>
" make arrows behave like gui text editor
nnoremap <up> gk
nnoremap <down> gj
inoremap <up> <C-O>gk
inoremap <down> <C-O>gj
vnoremap <up> gk
vnoremap <down> gj
</pre></noscript>
