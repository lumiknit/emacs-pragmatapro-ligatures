# emacs-pragmatapro-ligatures
[PragmataPro](https://www.fsd.it/shop/fonts/pragmatapro/) Font Ligatures 0.830 Support for Emacs

## Installation and Basic Usage

Download `pragmatapro-lig.el`, and add below to your `.emacs` or `init.el`:

```el
;; Load pragmatapro-lig.el
(add-to-list 'load-path "/PATH/TO/PRAGMATAPRO-LIG-EL")
(require 'pragmatapro-lig)

;; Enable pragmatapro-lig-mode for specific modes
(add-hook 'text-mode-hook 'pragmatapro-lig-mode)
(add-hook 'prog-mode-hook 'pragmatapro-lig-mode)
;; or globally
;;(pragmatapro-lig-global-mode)
```

You can toggle the ligature mode in the current buffer by `M-x pragmatapro-lig-mode`.

## Sample (0.828)

![sample-img](/sample.png)
