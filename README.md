# RCV1
Datasets RCV1_Region and RCV1_Topic
# The data and labels can be read with the following code. 
data = np.load(os.path.join(data_path, 'reut_all44.npy'), allow_pickle=True).item()
x = data['data']
y_region = data['regions_label']
y_topic = data['topic_label']
