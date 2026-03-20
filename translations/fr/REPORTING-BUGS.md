<!--TRANSLATION_LINKS_START-->
> 📖 **Versions disponibles dans d’autres langues** :[Anglais (en)](translations/en/REPORTING-BUGS.md) | [Espagnol (es)](translations/es/REPORTING-BUGS.md) | [Japonais (ja)](translations/ja/REPORTING-BUGS.md) | [Coréen (ko)](translations/ko/REPORTING-BUGS.md)
<!--TRANSLATION_LINKS_END-->

# Comment signaler les bogues

Si une quelconque partie du projet Nacos présente des bogues ou des erreurs de documentation, veuillez nous le faire savoir en [ouvrant un problème][Nacos-issue]. Nous prenons très au sérieux les bogues et les erreurs, et nous estimons qu'aucun problème n'est trop petit, tout le monde peut y contribuer. Avant de créer un rapport de bogue, veuillez vérifier qu'aucun problème similaire n'a déjà été signalé.

Pour que le rapport de bogue soit précis et facile à comprendre, veuillez essayer de créer des rapports de bogue qui sont :

- Spécifique. Incluez autant de détails que possible : quelle version, quel environnement, quelle configuration, etc. Si le bogue est lié à l'exécution du serveur Nacos, veuillez joindre le journal Nacos (le journal de démarrage avec la configuration Nacos est particulièrement important).
- Reproductible. Incluez les étapes pour reproduire le problème. Nous comprenons que certains problèmes peuvent être difficiles à reproduire, veuillez inclure les étapes pouvant mener au problème. Dans la mesure du possible, veuillez joindre le répertoire de données Nacos affecté et la trace de pile strace au rapport de bogue.
- Unique. Ne dupliquez pas un rapport de bogue existant.

Il peut être utile de lire l’article d’Elika Etemad sur la rédaction de bons rapports de bogue [filing-good-bugs] avant de créer un rapport de bogue.

Nous pourrions demander des informations supplémentaires pour localiser un bogue. Un rapport de bogue dupliqué sera fermé.

[etcd-issue]: https://github.com/etcd-io/etcd/issues/new
[filing-good-bugs]: http://fantasai.inkedblade.net/style/talks/filing-good-bugs/