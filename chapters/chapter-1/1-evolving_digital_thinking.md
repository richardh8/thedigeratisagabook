# Evolving digital thinking

>"To transform the world, which is to transform your social problem impacting people in the society, thinking counter intuitively is key to build the cornerstone of your research, salted with many and fast experimentations which will form your DNA in digital solutions to those problems in ways which no other technology organization would consider."

| Contact |
| :---: |
|![](../../images/evolving_digital_thinking.png)|
|Experimentation, research and formation of your digital DNA|

>In the movie "Contact", Ellie is a radio astronomer who, after much dedication, discovers and interprets an extraterrestrial signal. In this journey she constantly learns about knowledge from different areas, including technology, engineering, data, and biology to build a machine to travel in space-time.

## Rationale

## Abstract
The journey of digital transformation affects certain values ​​and principles that not every organization has embedded in its DNA and its foundation is in people's mentality and psychology. Statistical studies show that the main factor of positive impact on results in organizations is a psychologically safe environment, as it produces teams with high performance and a higher frequency of generating innovations. What is essential for any organization to remain competitive and relevant. The ability to adapt quickly to new customer expectations and trends in the digital environment are also factors that are constantly experienced.
Not accepting that the world is increasingly dynamic and causes uncertainty and continue to act in an excessively planned way, with long-term programs and projects, not only result in financial losses, but also in negative impacts on people's morale and engagement. This is where the philosophy of experimentation comes in to allow greater understanding and understanding of problems and solutions, and most importantly, rapid learning, before committing to greater investments in the production, development and delivery of new services. This practice reflects a kind of laboratory, where formulas can be tested and validated, before seeking production and replication at scale.

Implementing programs that allow people to have access to the customer and users, to be able to discuss the problem and collaborate in the design of solution proposals is already a big step, and allows research based on data and facts from outside and within the organization. Being able to employ proofs of concepts or value, which are centered on needs researched with customers, or originated by strategic actions, which integrate hypotheses based on data and the contribution of teams with ideas, technology, business models and marketing actions, will allow the organization understands in a given context how a possible solution would be. And so you can quickly test the quality and experience of this solution with a select group of customers, allowing a certain degree of co-creation. These actions reduce risks, allowing you to assess whether or not a particular solution moves forward to define the scope and design of the solution.
This process must be inserted in a controlled and monitored environment, evaluating the results, allowing changes to be implemented quickly and results observed practically in real time.

It has to be understood that having a psychologically-safe environment, helps to receive the failure of certain attempts, the most significant advances stem from several unsuccessful attempts. We must understand failure as part of the organization's learning process, allow the creation of a change of mind within the organization and lead to a culture of support and encouragement where people are more willing and able to share their ideas. Armed with data and a willingness to try new ideas, people can collaborate and create new experiences.

The more people involved in a company's success, the easier it is to understand its customer base and make informed decisions that generate business value. Leaders who encourage each employee to contribute their ideas create a viral effect, resulting in more people engaged in understanding their customers and becoming part of the solution. This type of training leads people to be more passionate about what they do, loyal and motivated.
Learning through experimentation is to encourage each person to contribute and create a culture that will help the organization obtain valuable information and transform the customer experience.

## Algorithm

```
import sys
from random import randint

#Domains assossiated with experiments, being one or across many
domain = (
	{ "name": "customer_employees", "trials": 0 },
	{ "name": "people", "trials": 0 },
	{ "name": "value",  "trials": 0 },
	{ "name": "ux",  "trials": 0 },
	{ "name": "technology",  "trials": 0 },
	{ "name": "partners",  "trials": 0 },
	{ "name": "business", "trials": 0 }
	)
#
capability = (
	{ "name": "iot", "trials": 0 },
	{ "name": "mobile", "trials": 0 }, 
	{ "name": "social_media", "trials": 0 },
	{ "name": "big_data", "trials": 0 },
	{ "name": "analytcs", "trials": 0 },
	{ "name": "artificial_intelligence", "trials": 0 },
	{ "name": "machine_learning", "trials": 0 },
	{ "name": "cloud", "trials": 0 },
	{ "name": "api", "trials": 0 },
	{ "name": "cybersecurity", "trials": 0 }
	)
#
maturity = (
	"learner", "apprentice", "practitioner", 
	"experimenter", "transformer", "innovator"
	)

evolutions = 0
experiments = []

trials = 2


class DigitalDNA(object):
	def __init__(self, domain, capability, maturity, failures, learnings, speed):
		self.domain = domain
		self.capability = capability
		self.maturity = maturity
		self.failures = failures
		self.learnings = learnings
		self.speed = speed

def try_domains():
	domains = [];
	variations = randint(0, 8)
	for i in range(variations):
		domains.append(domain[randint(0, len(domain)-1)]["name"])
	return domains

def try_capabilities():
	capabilities = [];
	variations = randint(0, 8)
	for i in range(variations):
		capabilities.append(capability[randint(0, len(capability)-1)]["name"])
	return capabilities


def track_maturity(domains, capabilities):
	#if any(x in paid[j] for x in d):
	
	return ""

def show_digital_dna_evolution(experiments):
	for i in range(len(experiments)):
		print("Trial ", i,
			experiments[i].domain,
			experiments[i].capability,
			experiments[i].maturity,
			experiments[i].failures,
			experiments[i].learnings,
			experiments[i].speed,
			sep="\n"
			)

try:
	for i in range(trials):
		experiments.append(
			DigitalDNA(
				try_domains(),
				try_capabilities(),
				maturity[randint(0, len(maturity)-1)],
				["failure point 1", "failure point 2", "failure point 3"],
				["learning point 1", "learning point 2", "learning point 3"],
				2
			)
		)
		evolutions += 1
	show_digital_dna_evolution(experiments)
except:
	print("Unexpected error:", sys.exc_info())
```

## Narrative

## Examples
