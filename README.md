# bogue-signaler-
Demande de signaler ce bogue ?
Oups, un problème s'est produit. Signalez ce bogue avec les détails ci-dessous.
Rapport sur GitHub : https://github.com/lzybkr/PSReadLine/issues/new
-----------------------------------------------------------------------
113 dernières touches :
 f a s t b o o t . e x e Spacebar - i Spacebar 0 x 0 f c e Spacebar g e t v a r Spacebar v e r s i o n Enter
 . Ctrl+Alt+< f a s t b o o t . e x e Enter
 Ctrl+v Enter
 f a s t b o o t Spacebar - i Spacebar 0 x 0 f c e Spacebar o e m Spacebar d é v e r r o u i l l e r Spacebar 0 x D E 3 8 1 0 1 D B 6 8 A A 0 D E 0 Enter
 Ctrl+c

Exception :
System.ArgumentOutOfRangeException: La valeur doit être supérieure ou égale à zéro et inférieure à la taille de la mémoire tampon de la console dans cette dimension.
Nom du paramètre : left
La valeur réelle était 97.
   à System.Console.SetCursorPosition(Int32 left, Int32 top)
   à Microsoft.PowerShell.PSConsoleReadLine.ReallyRender()
   à Microsoft.PowerShell.PSConsoleReadLine.CancelLine(Nullable`1 key, Object arg)
   à Microsoft.PowerShell.PSConsoleReadLine.CopyOrCancelLine(Nullable`1 key, Object arg)
   à Microsoft.PowerShell.PSConsoleReadLine.ProcessOneKey(ConsoleKeyInfo key, Dictionary`2 dispatchTable, Boolean ignoreIfNoAction, Object arg)
   à Microsoft.PowerShell.PSConsoleReadLine.InputLoop()
   à Microsoft.PowerShell.PSConsoleReadLine.ReadLine(Runspace runspace, EngineIntrinsics engineIntrinsics)
-----------------------------------------------------------------------
