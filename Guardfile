# More info at https://github.com/guard/guard#readme

notification :off

guard 'livereload' do
  watch(%r{.+\.(css|js|html)})
end

guard :haml, run_at_start: true do
  watch(/^.+((\.html)?\.haml)$/)
end

guard 'coffeescript', input: 'js', all_on_start: true, hide_success: true
guard 'sass', input: 'css', all_on_start: true, hide_success: true
