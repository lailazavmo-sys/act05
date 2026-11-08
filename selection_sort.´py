def seleccion_ascendente(arreglo):
    n = len(arreglo)
    for i in range(n - 1):
        min_idx = i
        for j in range(i + 1, n):
            if arreglo[j] < arreglo[min_idx]:
                min_idx = j
        if min_idx != i:
            temporal = arreglo[i]
            arreglo[i] = arreglo[min_idx]
            arreglo[min_idx] = temporal
        print(f"Pasada {i + 1}: {arreglo}")
    return arreglo


datos = [25.4, 12.8, 35.1, 4.2, 18.5]
print("Original:", datos)
print("Ordenado:", seleccion_ascendente(datos))
