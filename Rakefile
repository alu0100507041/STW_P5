desc "Ejecutar servidor"
task :default do
  sh "ruby config.ru"
end

desc "Ejecutar pruebas unitarias"
task :test do
  sh "ruby -Ilib test/tc_piedra.rb"
end
