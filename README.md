class Attributes(tech):
    @staticmethod
    def life() -> tuple:
        langs = ['Romanian', 'English']
        nationalities = self.langs.remove('Romanian', 'English')
        age = 24
        return langs, nationalities, age

    @staticmethod
    def coding() -> tuple:
        langs = {
            'expert':   ['python', 'java'],
            'intermediate': ['ts', 'js'],
            'learning': ['c', 'c++', 'c#', 'asm']
        }
        specialities = ['web/app', 'fullstack']
        environnement = ['vscode', 'intellij']
        return langs, specialities, environnement
