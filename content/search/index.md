+++
layout = 'search'
noindex = true
title = 'Search'

[form]
  helpblock = 'Press <kbd>/</kbd> or <kbd>s</kbd> to modify your search.'
  hotkeys = ['/', 's']

  [form.input]
    disabled = false
    placeholder = 'uzzy searvh'

[security]
  [security.csp]
    [security.csp.directives]
      scriptSrc = ["'sha512-6G7cmlXR4eLBphfUmmEWLEnLWSEtZPdKP2xv7bXZ8D3LReZazwxcwb4tTx2HeCeoAChG5ZCE+UqHmbe3K4xoJg=='", "'unsafe-eval'"]
+++
