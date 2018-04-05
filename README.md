# PoliTwit

## Examining political speech on social media

#### Dataset

* Origin: 
    * Crowdflower Data for Everyone dataset: https://www.crowdflower.com/data-for-everyone/
    * https://www.kaggle.com/crowdflower/political-social-media-posts/data
* Meta-data:
    * _unit_id: a unique id for the message
    * _golden: always FALSE; (presumably whether the message was in Crowdflower's gold standard)
    * _unit_state: always "finalized"
    * _trusted_judgments: the number of trusted human judgments that were entered for this message; an integer between 1 and 3
    * _last_judgment_at: when the final judgment was collected
    * audience: one of national or constituency
    * audience:confidence: a measure of confidence in the audience judgment; a float between 0.5 and 1
    * bias: one of neutral or partisan
    * bias:confidence: a measure of confidence in the bias judgment; a float between 0.5 and 1
    * message: the aim of the message. one of: 
        * attack: the message attacks another politician 
        * constituency: the message discusses the politician's constituency 
        * information: an informational message about news in government or the wider U.S. 
        * media: a message about interaction with the media 
        * mobilization: a message intended to mobilize supporters 
        * other: a catch-all category for messages that don't fit into the other 
        * personal: a personal message, usually expressing sympathy, support or condolences, or other personal opinions 
        * policy: a message about political policy 
        * support: a message of political support
    * message:confidence: a measure of confidence in the message judgment; a float between 0.5 and 1
    * orig__golden: always empty; presumably whether some portion of the message was in the gold standard
    * audience_gold: always empty; presumably whether the audience response was in the gold standard
    * bias_gold: always empty; presumably whether the bias response was in the gold standard
    * bioid: a unique id for the politician
    * embed: HTML code to embed this message
    * id: unique id for the message WITHIN whichever social media site it was pulled from
    * label: a string of the form "From: firstname lastname (position from state)"
    * message_gold: always blank; presumably whether the message response was in the gold standard
    * source: where the message was posted; one of "facebook" or "twitter"
    * text: the text of the message
    
#### Goal

Seeking to understand statistical relationships between certain words and certain message types as determined by qualified human assessors. 

#### Data provenance and trustworthiness considerations
#### Data cleaning
#### Data meanings and confidence usage in statistical look
