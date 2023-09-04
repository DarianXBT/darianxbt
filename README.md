



class Attributes(Darian):
	@staticmethod
	def channels() -> tuple:
            discord  = "/"
	    telegram = "t.me/onlpx"

            return discord, telegram

	@staticmethod
	def contact() -> tuple:
	    discord  = "dqryqn"
	    telegram = "/"
	    email    = "/"
	    
	    return discord, telegram, proton
	
	@staticmethod
	def life() -> tuple:
		langs         = ['German', 'English', 'Spanish', 'Yugoslavian']
		age           = 16
		
		return langs, age
	
	@staticmethod
	def coding() -> tuple:
		langs = {
			'expert':   ['java'],
			'intermediate': ['python', 'js'],
			'learning': ['c', 'c++', 'c#']
		}
		specialities  = ['web/app reverse engineering', 'fullstack']
		environnement = ['vscode']
		
		return langs, specialities, environnement
