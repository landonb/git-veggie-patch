@@@@@@@@@@@@@@@@
git-veggie-patch
@@@@@@@@@@@@@@@@

#####
USAGE
#####

Injects a colorful flower bed atop each hunk of a ``git add -p``
interactive patch session.

.. image:: assets/git-veggie-patch-example.png

`Read my article <https://tallybark.com/post/git-vegetables/>`__
on Tally Bark.

#####
SETUP
#####

`Copy from <https://github.com/landonb/git-veggie-patch/blob/master/.gitconfig.example#L2-L3>`__
``.gitconfig.example`` to your user's ``~/.gitconfig``,
or run the command::

  git config --global interactive.diffFilter diff-filter-garden

#######
CAVEATS
#######

Git will not call ``diffFilter`` unless ``ui.color`` is enabled.

