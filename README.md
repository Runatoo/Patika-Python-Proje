# Patika-Python-Proje

# ilk proje

def flatten(lst):
    flattened_list = []
    for i in lst:
        if isinstance(i, list):
            flattened_list += flatten(i)
        else:
            flattened_list.append(i)
    return flattened_list


# ikinci proje
2- Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün. Örnek olarak:

input: [[1, 2], [3, 4], [5, 6, 7]]

output: [[[7, 6, 5], [4, 3], [2, 1]]

# Çözümü

l1 =  [[1, 2], [3, 4], [5, 6, 7]]

a = l1[0][::-1], l1[1][::-1], l1[2][::-1]
a[::-1]
