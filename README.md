def find_triplet_with_sum(numbers):
    # Izveido vārdnīcu, kurā tiek glabātas kartīšu vērtības un to biežumi
    number_count = {}
    for num in numbers:
        number_count[num] = number_count.get(num, 0) + 1

    # Iterēt pāri katram pārim (A, B)
    n = len(numbers)
    for i in range(n):
        for j in range(i + 1, n):
            A = numbers[i]
            B = numbers[j]
            C = A + B
            # Pārbauda, vai C eksistē un ir atšķirīgs no A un B
            if C in number_count:
                # Pārbauda, vai C nav dublikāts no A vai B
                count_required = (C == A) + (C == B)
                if number_count[C] > count_required:
                    print(1)
                    print(A, B, C)
                    return
    
    # Ja trijnieku neatrod
    print(0)

# Ievades apstrāde
N = int(input())
numbers = list(map(int, input().split()))

# Atrisināt problēmu
find_triplet_with_sum(numbers)

