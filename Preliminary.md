## Initial setup

1. GitHub
   * Sign up for [GitHub](https://github.com/) if not already signed
     up. Pick default (free plan).
   * [Create ssh key](https://help.github.com/articles/generating-ssh-keys/)
   
            - Do steps 1, 2, 4, and 5
            - Do Not Share Your Private Key in id_rsa
   * [Fork](https://help.github.com/articles/fork-a-repo/) and create a [pull request](https://help.github.com/articles/using-pull-requests/) on [students repository](https://github.com/fdac21/students) so I
      can add you to the to the GitHub group for the course.
      
            - Start by [**forking** the students repository](https://github.com/fdac21/students)
            - Add your utk net id as NETID.md (click on '+' - add 
               new file next to the https//github.com/fdac19/students/+ link)
            - Add your UTK netid and publickey key (in id_rsa.pub) to
               NETID.key
            - Click on Create Pull Request (do not create NETID.md, but replace NETID by your netid in all lowercase)
1. Familiarize yourself with GitHub workflow
   * Walk through [workflow](#workflow) 
    
## Typical workflow
1. To start, [**fork** the repository][forking] for the test project (found under [github.com/fdac21](https://github.com/fdac21))
1. [**Clone**][ref-clone] the repository to your computer.
1. View, create, and edit your files
1. [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository


Feedback will be given in the pull request, so please respond with
your thoughts and questions!  You are welcome to open the pull
request as the work is still in-progress if you are stuck and want
to ask a question – just mention `@audris` with the question to make
sure I know to look at it sooner.

## Initial setup: to be done on/by Aug 26 on


## Configuring ssh 
  * On linux/mac
     * create .ssh/config
    	1. create ~/.ssh/config
        ```
         host da2
            hostname da2.eecs.utk.edu
            port YOURPORT #from students/ports.md
            user YOURNETID
            LocalForward 8888 127.0.0.1:8888
            IdentityFile ~/.ssh/id_rsa
            StrictHostKeyChecking no
            UserKnownHostsFile /dev/null
         ```

        1. place your private key in ~/.ssh/id_rsa
        1. Make sure permissions are right
         ```
          chmod -R og-rwx ~/.ssh
         ```
        1. ssh da2
    * Or ssh directly 
      ```
       ssh -pYOURPORT -L8888:localhost:8888 -i ~/.ssh/id_rsa yournetid@da2.eecs.utk.edu
      ```
  * Windows 10 has ubuntu subsystem: use that please
https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_overview


  * Putty is an ssh client for earlier versions of windows, please avoid if you have Win10 or later
  * [Instructions on how to generate ssh key running windows](https://docs.joyent.com/public-cloud/getting-started/ssh-keys/generating-an-ssh-key-manually/manually-generating-your-ssh-key-in-windows) 

       1. How to generate key via putty
       1. ![generate the key via puttygen](https://github.com/fdac21/news/blob/master/PuttyGen.png "generate new key puttygen")

       1. Copy the key
       1. ![public ssh key from puttygen](https://github.com/fdac21/news/blob/master/puttykey.png "public ssh key from puttygen")

       1. Save the private key and use it in your putty ssh session
       1. Copy the public key (highlited in the image) to add to the yournetid.key 
       1. Now work on creating and saving session: start putty and go to connection/ssh/tunnels, enter source and destination and click *add*
       1. ![port forwarding](https://github.com/fdac21/news/blob/master/puttyport.png "select port forwarding")

       1. Go to  go to connection/ssh/Auth and browse for your private key
       1. ![authentication](https://github.com/fdac21/news/blob/master/puttyauth.png "select secret key that was saved above")
       1. Go to  go to session enter hostname and *YOUR PORT* from ports.md in fdac/students
       1. ![session](https://github.com/fdac21/news/blob/master/puttysession.png "start putty session")
       1. Don't forget to _save_ the session before clicking open  


<!-- Links -->
[docker]:http://www.eecs.utk.edu/resources/it/kb/docker
[deliberate-practice]:http://www.psy.fsu.edu/faculty/ericsson/ericsson.exp.perf.html
[pull-request]:https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
