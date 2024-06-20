# Les différents wallet et l'évolution progressive de l'Account Abstraction

<figure><img src="../../.gitbook/assets/image (275).png" alt=""><figcaption><p><a href="https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing">https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing</a></p></figcaption></figure>

Le site web [Realt.co](https://realt.co/) est une application Web2 qui s’accède de façon classique avec un identifiant et un mot de passe (auquel, en option, vous pouvez ajouter une sécurité supplémentaire avec un second code : fonction 2FA).\
Pour autant, les tokens que vous achetez et les loyers que vous percevez ne sont pas détenus par RealT (ou sur l’application Realt.co), mais sont stockés sur un wallet (même dans le cas de l’option « walletLess » !)

Les applications qui fonctionnent sur la blockchain (qualifés de DApp : Application décentralisée ou Web3), ne s’accèdent qu’avec une clé privé (stokée dans Metamask, ou Ledger,..).\
C’est par exemple le cas des deux DApp : YAM (pour acheter et vendre des Realtoken) et RMM (pour déposer et emprunter avec des Realtoken). Ces deux applications peuvent faire des transactions sur votre wallet (avec votre approbation). D’autres applications communautaires (Dashboard, Crypt’Alloc, Pit’swap, ..), elles vous demandent juste votre clé publique pour lire l’état de votre wallet (pour toute transaction, elles renvoient à YAM ou Swapcat).

La fonction Walletless, ne permet pas d'accéder aux DApp, ce que le nouveau Abstract Account permettra progressivement:&#x20;

* Etape 1 : Tout se fera à partir du site Realt.co.&#x20;
  * La création du "RealT Wallet" (Abstract Account) sans vous soucier de la clé privée, qui sera répartie sur trois adresses et sécurisée par RealT (ou par l'utilisateur lui même, si il le souhaite),
  * Accès au YAM et au RMM (uniquement pour le dépôt).
* Etape 2 : Les DApp de l'écosystème seront progressivement mis à niveau pour accepter les wallet AA (YAM, puis RMM). Il sera alors possible pour ces wallets de ne plus passer par le site Realt.co et d'accéder à des fonctions supplémentaires (emprunt RMM par ex.)
* Etape 3 : Une application spécifique pour les wallet AA sera développée pour :&#x20;
  * accéder aux DApp qui ne supporteraient ce standard, et cela au travers de la solution Wallet Connect 2 (comme cela se fait actuellement sur mobile),
  * accéder aux fonctions programmables, qui seront mis en place dans la partie Smart Contract de l'abstract Account.

Nota : de nouvelles versions du standard d'Abstraction Account sont en cours d'étude et nécessiteront très certainement des migrations durant toute cette évolution.