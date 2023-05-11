# Денис Цветков
# CONTACTS
- Vitebs, Belarus

- Email: denistsvetkov2@gmail.com

- Github: https://github.com/DenisTsvetkovGit

# SUMMARY
> I am a student at P.M. Masherov University of Eastern Europe, majoring in Information Resource Management. My goal is to become a professional in the field of information technology and apply my knowledge in various areas of business. I am motivated, diligent and love to learn new things. My strengths are analytical mind, communication skills, responsibility.
# SKILLS

1. С++
2. HTML
3. CSS
4. Assembler
5. Adobe Photoshop

# CODE
```
void quicksort(vector<int>& arr, int left, int right) {
    int i = left, j = right;
    int pivot = arr[(left + right) / 2];

    while (i <= j) {
        while (arr[i] < pivot) {
            i++;
        }

        while (arr[j] > pivot) {
            j--;
        }

        if (i <= j) {
            swap(arr[i], arr[j]);
            i++;
            j--;
        }
    }

    if (left < j) {
        quicksort(arr, left, j);
    }

    if (i < right) {
        quicksort(arr, i, right);
    }
}

int main() {
    vector<int> arr = { 3, 7, 1, 9, 2, 4, 5, 6, 8 };
    quicksort(arr, 0, arr.size() - 1);

    for (int num : arr) {
        cout << num << " ";
    }
    cout << endl;

    return 0;
}
```

# COURSES
+ Экономика организации
+ Компьютерная графика

# PROJECTS

Моё СV на GitHub: [https://github.com/DenisTsvetkovGit/CV/blob/markdowm-cv/cv.md](https://github.com/DenisTsvetkovGit/CV/blob/markdowm-cv/cv.md)

# EDUCATION

* Vitebsk State University named after P.M. Masherov

# ENGLISH

* A2+ Pre-Intermediate


