
# Regex Lab

This is a test driven ruby lab designed to get you comfortable using Regex in combination with the `.match` and `.scan` methods. Run `learn` and build out your methods in regex_lab.rb
<p data-visibility='hidden'>View <a href='https://learn.co/lessons/regex-lab' title='Regex Lab'>Regex Lab</a> on Learn.co and start learning to code for free.</p>


#first_word_capitalized_and_ends_with_punctuation? Returns false for text starting with an uncapitalized letter but ending with punctuation       

#Returns false for text starting with a capital letter but ending without puncutation                                                                                     

def first_word_capitalized_and_ends_with_punctuation?(text)
  if text == /[A-Z][a-z]{1,}./
    return true
  elsif text == /[A-Z][a-z]/
    return false
  end
end

#first_word_capitalized_and_ends_with_punctuation? Returns false for text starting without a # capital letter and ending withoutpunctuation                                                                                             
# Working with Regular expressions #valid_phone_number? returns true for valid phone numbers, regardless of formatting
