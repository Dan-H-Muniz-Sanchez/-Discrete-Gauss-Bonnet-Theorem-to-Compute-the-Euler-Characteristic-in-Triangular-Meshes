
# Program for Calculating Gaussian Curvature and Euler Characteristic

This Python program utilizes the PyMeshLab library to calculate Gaussian curvature and apply the Gauss-Bonnet theorem to compute the Euler characteristic of various triangular meshes.

## Requirements

- Python 3.x
- PyMeshLab
- NumPy

## Installation of Dependencies

```bash
pip install pymeshlab numpy
```



## Example
This is de *Gauss Bonnet Theroem - (discrete version)*

![discrete gauss-bonnet](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/424f07ad-36a8-4a2d-875c-aa1770477966)

We define the $K(v)$ as the Gaussian Curvature of every each vertex in the mesh

![curvatur_of_vertices](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/dda6f4c8-f386-4497-b84f-88ea5f923eb7)

other implementation using mixed voronoi areas are 

![k(v)_mixed](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/d9e9c2f7-9f45-41cf-a34b-76692303c736)

by Mixed Voroni Areas we are talkin about  this 

![Voronoi_mixed](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/667909df-e7e8-4d61-927d-75098e3edeb7)

The algorithm to calculate is 

![voronoi_mixed_algoritmh](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/b07a69bd-1b36-4070-bcb7-8a280f286f7a)


To calculate the Gaussian curvature of a triangular mesh named `face.obj`:



## Contributing

If you'd like to contribute to the development of this program, feel free to send pull requests.

## RESULTS

![FACE](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/44a2a2ba-45ba-413a-8bf4-e94f54a06d93)
Gaussian Cruvature over a face.obj (Triangular Mesh)

And 

![SILLA](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/2d6460e9-31ff-444f-9eb1-dae22ed1ecfc)
 we obtain the euler characteristic number of this triangular mesh is 0 $\chi(M) = 0$
 and thats mekaes sense with the continuous idea  like this 

 

![Screenshot 2024-02-07 175841](https://github.com/Dan-H-Muniz-Sanchez/-Discrete-Gauss-Bonnet-Theorem-to-Compute-the-Euler-Characteristic-in-Triangular-Meshes/assets/147218204/e2f74264-1a44-4441-b9c1-41f121d87622)


## License

