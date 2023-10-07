# A prompt contains any of the following elements:
* Instruction - a specific task or instruction you want the model to perform
* Write, classify, summarize, translate, order
* Use separators
### Instruction - a specific task or instruction you want the model to perform
* Write
* Classify
* Summarize
* Translate
* Order

### Don't forget to use separators
"""Instruction""" <br>
 Translate the text  to Spanish: Text: "hello!"<br>

### Specificity
* Be very specific about the instruction and task you want the model to perform.
* The more descriptive and detailed the prompt is, the better the results.
* Example
  * Extract the name of places in the following text.
  * """Desired format""" Place: <comma_separated_list_of_company_names>
  *  """Text""" "Although these developments are encouraging to researchers, much is still a mystery. “We often have a black box between the brain and the effect we see in the periphery,” says Henrique Veiga-Fernandes, a neuroimmunologist at the Champalimaud Centre for the Unknown in Lisbon. “If we want to use it in the therapeutic context, we actually need to understand the mechanism.""

### Avoid Impreciseness
* Don't get too clever.
* Be specific and direct.
* Example
  * Use 2-3 sentences to explain the concept of prompt engineering to a high school student.

### Say what you want the prompt to do, not what you want the prompt not to do
* Example
  * "Please use simple and easy-to-understand language in the explanation."
  * *NOT* "Don't use complex words in the explanation."


