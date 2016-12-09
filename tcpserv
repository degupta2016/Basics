
#include <sys/types.h>
#include <sys/socket.h>
#include <netinet/in.h>
#include < stdio.h>

main()
{
    /* create socket */
    sock = socket(AF_INET, SOCK_STREAM, 0);
    if ( sock < 0 ) {
       perror( "Error opening socket!\n");
       exit(1);
     }
     /* initialize */
     server.sin_family = AF_INET;
     server.sin_addr.S_un.S_addr = INADDR_ANY;
     server.sin_port = 0;
     
     /* bind */
     if ( bind( sock, &server, sizeof(server)) {
        perror( "Error binding socket!\n");
        exit(1);
     }
     
  }
     
        
       
