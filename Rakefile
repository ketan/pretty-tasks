desc "default"
task :default do
  longest_key = ENV.to_h.keys.sort_by(&:length).last.length
  ENV.to_h.each do |k, v|
    puts "#{k.rjust(longest_key)} = #{v}"
  end
end
