FROM ubuntu:14.04
ENV my_env my_value
RUN echo ${my_env:-value} / ${my_env:+value} / ${my_env2:-value} / ${my_env2:+value} 
