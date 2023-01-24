# stickyNotes
The project "why are you here?" aims to build a facial recognition and access control system for surveillance cameras using deep learning models. The system would detect human bodies in recorded videos, crop the faces from the images, convert the faces to embedding vectors, and then compare them to the embedding vectors of employees in a registry. This would allow the system to identify which employees were present in the video footage. After identification, the system would then check the database to see if the identified employee has access to the area being monitored by the surveillance camera. The project requires a diverse set of labeled images to train the facial recognition model.

Proposing a machine learning project to assist in the process of reconciling data between two datasets, where one dataset represents "We" or the source, and the other represents "They" or the target. The project would have two modes of operation:

Automated alignment of columns based on column name, datatype, and match percentage, with final alignment decisions to be made by a human.
A user-assisted mode where a user can select a column on one side, and the machine learning model would recommend likely matching columns on the other side.
