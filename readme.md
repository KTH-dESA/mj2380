# MJ2380 Lecture 3 - Island Model using GNU MathProg

Provides the model and data for a simple island model.

Run the model glpsol:

    glpglpsol -d island_data.txt -m island_model.txt -o results.txt

View the LP file by appending `--wlp island.lp` to the command above.

## License

You are free to use the model and data under the terms of the open source MIT license.
See `license.txt`.
