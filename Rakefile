namespace :book do
  
  desc "Comprueba sintaxis"
  task :aspell do
    system("cat curso/*md | aspell list -d es -p ./.aspell.es.pws")
  end
  
end