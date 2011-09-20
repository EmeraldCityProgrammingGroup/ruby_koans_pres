!SLIDE title
#Working with Ruby Koans#

!SLIDE bullets
#What are Ruby Koans#

* Set of unit test for Test Driven Learning
* Fill in the blanks 
!SLIDE commandline small
#Create Working Space#
    $ git checkout -b ad-work

!SLIDE commandline smaller
#Running the Koans#
    $ rake
    
    rake/rdoctask is deprecated.  Use rdoc/task instead (in RDoc 2.4.2+)
    /Users/alley/.rvm/rubies/ruby-1.9.2-p290/bin/ruby path_to_enlightenment.rb
    AboutObjects#test_every_object_has_an_id has expanded your awareness.
    AboutObjects#test_every_object_has_different_id has expanded your awareness.
    AboutObjects#test_some_system_objects_always_have_the_same_id has damaged your karma.
    
    The Master says:
      You have not yet reached enlightenment.
      You are progressing. Excellent. 13 completed.
    
    The answers you seek...
    <"FILL ME IN"> expected but was  <0>.
    
    Please meditate on the following code:
      /Users/alley/Projects/emerald_city/ruby_koans/koans/about_objects.rb:34:in 
      `test_some_system_objects_always_have_the_same_id'
    
    remember that silence is sometimes the best answer
    your path thus far [..X_______________________________________________] 13/276

!SLIDE code smaller
#Editing a Koan#
    @@@ ruby
    
    def test_assert_with_message
      assert false, "This should be true -- Please fix this"
    end
  
    # To understand reality, we must compare our expectations against
    # reality.
    def test_assert_equality
      expected_value = __
      actual_value = 1 + 1
  
      assert expected_value == actual_value
    end

!SLIDE commandline small
#Comminting code back to the branch#
    $ git commit -am "completed koan file"

!SLIDE title
# Live Koans#
