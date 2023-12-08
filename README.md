# 101pong : Epitech Project

The goal of this project is to work on a 3D version of this game (or of the Breakout game. . . ). Only one paddle
will be considered, located in the (Oxy) plane (which is defined by the equation z = 0).

### Installation

To use this project clone the repository or download it to .zip file format.

## Make file

This project use Makefile so here's a little tutorial : 

To compile and get the binary executable use :
```
make 
```
To clear the repository from .o files use : 
```
make clean 
```
To fully clear the repository from any compiled files, .o and executable use :
```
make fclean
```
To recompile without clearing the repository use :
```
make re 
```
### Usage

```
> ./101pong -h
USAGE
./101pong x0 y0 z0 x1 y1 z1 n
DESCRIPTION
x0 ball abscissa at time t - 1
y0 ball ordinate at time t - 1
z0 ball altitude at time t - 1
x1 ball abscissa at time t
y1 ball ordinate at time t
z1 ball altitude at time t
n time shift (greater than or equal to zero, integer)
```

Example : 

```
 ./101pong 1.1 3 5 -7 9 2 4
The velocity vector of the ball is:
(-8.10, 6.00, -3.00)
At time t + 4, ball coordinates will be:
(-39.40, 33.00, -10.00)
The incidence angle is:
16.57 degrees
```
