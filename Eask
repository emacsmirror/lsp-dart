;; -*- mode: eask; lexical-binding: t -*-

(package "lsp-dart" "1.24.3" "Dart support lsp-mode")

(website-url "https://emacs-lsp.github.io/lsp-dart")
(keywords "languages" "extensions")

(package-file "lsp-dart.el")

(files "*.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source 'gnu)
(source 'melpa)

(depends-on "emacs" "28.1")
(depends-on "lsp-treemacs")
(depends-on "lsp-mode")
(depends-on "dap-mode")
(depends-on "f")
(depends-on "dash")
(depends-on "dart-mode")
(depends-on "jsonrpc")
(depends-on "ht") ; Remove after plists is implemented

(development
 (depends-on "el-mock")
 (depends-on "ert-runner")
 (depends-on "undercover")
 (depends-on "spinner"))

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432
