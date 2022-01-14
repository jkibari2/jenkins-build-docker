nœud{
  application par défaut

    stage( ' Cloner ' ) {
        caisse scm
    }

    stage( ' Créer une image ' ) {
        app = docker . build( " srv-web " )
    }

    stage( ' Exécuter l'image ' ) {
        docker . image( ' srv-web ' ) . withRun( ' -p 800:80 --name srv_web ' ) { c  ->

        sh ' docker ps | grep srv-web '

      

    }

    }
    
}
