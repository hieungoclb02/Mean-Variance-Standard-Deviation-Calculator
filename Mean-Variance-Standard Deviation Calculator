import numpy as np

def calculate(list2):
    if len(list2)!=9:
        raise ValueError('List must contain nine numbers.')

    list1= np.array(list2)
    list1=list1.reshape(3,3)
    calculations = {}
    calculations['mean']=[np.mean(list1, axis=0).tolist(),np.mean(list1,axis=1).tolist(),np.mean(list1).tolist()]
    calculations['variance']=[np.var(list1, axis=0).tolist(),np.var(list1,axis=1).tolist(),np.var(list1).tolist()]
    calculations['standard deviation']=[np.std(list1, axis=0).tolist(),np.std(list1,axis=1).tolist(),np.std(list1).tolist()]
    calculations['max']=[np.max(list1, axis=0).tolist(),np.max(list1,axis=1).tolist(),np.max(list1).tolist()]
    calculations['min']=[np.min(list1, axis=0).tolist(),np.min(list1,axis=1).tolist(),np.min(list1).tolist()]
    calculations['sum']=[np.sum(list1, axis=0).tolist(),np.sum(list1,axis=1).tolist(),np.sum(list1).tolist()]



    return calculations
