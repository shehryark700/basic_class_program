# basic_class_program
Introduction to class and objects
class ZAHIDKHAN_FAMILY:
    Name =''
    Khusrae_nachai= False
    ##
    def _init_(self):
        self.Name = 'Abdullah'
        self.Khusrae_nachai= False

    def baby_settings (self,var=False):
        self.Name=input('Please enter new baby name:')
        self.Khusrae_nachai=True

    def Show_data(self):
        print ('The child name: '+self.Name + '\nHaaan ji..Khusrae nachaee:',self.Khusrae_nachai)
##
Shehry_instance = ZAHIDKHAN_FAMILY()    #84 Bytes
Shehry_instance.baby_settings()
Shehry_instance.Show_data()
