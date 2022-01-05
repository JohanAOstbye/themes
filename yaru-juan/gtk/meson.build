flavours = []
foreach flavour: ['default', 'dark', 'juan']
  if not get_option(flavour)
    message('skip flavour ' + flavour)
    continue
  endif
  flavours += flavour
endforeach


subdir('src')
