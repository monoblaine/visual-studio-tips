# Git Source Control Plugin'ini devre dışı bırakma

1. `Team Explorer` penceresini asla açma, açıksa hemen kapat. _(Kaynak: http://stackoverflow.com/questions/21150060/how-can-you-disable-git-integration-in-visual-studio-2013-permanently#comment58087935_32036251)_
2. Solution'ı kapat (`Close Solution`)
3. `Tools > Options > Source Control > Plug-in Selection` sayfasındaki açılır menüden "None"ı seç. _(Kaynak: http://stackoverflow.com/a/32036251/1396155)_
4. _(Kaynak: http://stackoverflow.com/a/32304978/1396155)_
    1. Run `regjump HKEY_CURRENT_USER\Software\Microsoft\VisualStudio\14.0\TeamFoundation\GitSourceControl\Repositories`
    2. "Repositories" entry'sinin altındaki öğeleri sil.
    3. Run `regjump HKEY_CURRENT_USER\Software\Microsoft\VisualStudio\14.0\TeamFoundation\GitSourceControl\General\LastUsedRepository`
    4. `LastUsedRepository` öğesini sil.
