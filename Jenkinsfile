

node {
  echo Program;
  echo Branch;
  git url: 'https://github.com/schechter/workflow-test', branch: Branch;
  echo 'here';
}
env.Program = Program
node {
  echo Program
  sh 'sh builds.sh $Program'
}
