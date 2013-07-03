A way to create and open a file in its default application at the same time from bash.
Paste the following text anywhere in ~/.bash_profile
***



ltouch()
{
  touch $1
  open $1
}
