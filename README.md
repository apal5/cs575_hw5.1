# cs575_hw5.1
[Google Collab Link](https://colab.research.google.com/drive/1FjZ9ddqvlwcRbEcBUJRbfZaiSpvlu_x4?usp=share_link)
## Compare performance of Merge Sort and Quick Sort for a very large data set.
Reasons to prefer Quick Sort over Merge Sort
| Sorting Technique | Best Case | Average Case | Worst Case |
| --- | --- | --- | --- |
| Merge Sort | Ω(n log(n)) | θ(n log(n))	 | O(n log(n)) |
| Quick Sort | Ω(n log(n)) | θ(n log(n))	 | O(n^2) |

1. Merge Sort takes extra memory where as quick-sort works in place
2. Runtime of Merge Sort shoots up dramatically for larger input sizes and Quick Sort on the contrary performs much better even when worst case the growth rate of Quick Sort is worse than Merge Sort.
<img width="739" alt="image" src="https://user-images.githubusercontent.com/113304768/205466135-8bb539ba-dbb8-4548-914b-217312921860.png">
