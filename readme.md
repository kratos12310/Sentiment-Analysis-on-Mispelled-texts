To do Sentiment Analysis on Mispelled text

Firstly, Keep the indic.py, char3_edited_model.h5 and eng_char_vector.pickle in the destination of the programm where indic.py will be called
	
import indic.py as ind

sentiment,acc=sentiment(text)     where text is the eng mispelled text on which sentiment analysis will be done
	
sentiment contains the polartity and acc stores the accuracy 