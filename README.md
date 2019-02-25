# comment-or-uncomment-sexp

Emacs-lisp command for inteligently commenting and commenting the sexp
under point.

For more details and visual demonstration [see my blog post about
it](http://endlessparentheses.com/a-comment-or-uncomment-sexp-command.html).

To make it easier to use, consider binding it:

```emacs-lisp
(global-set-key (kbd "C-M-;") #'comment-or-uncomment-sexp)
```
