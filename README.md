# bmjtm
bluemoon´s java templates - main repo
provides templates for the software bluemoon to create runnable jars
\nIf you want to provide your own ones, simply create an github repo, add the same folderstructure:
./templates
  <random name>.blmo
  etc.
.blmo files structure:
c<name of command>
p_<variable type1>:<variable name1>_<variable type2>:<Variable name2>=<predifined value>
r_<import1>_<import2>
{
   //here the input code 
}
