# Nombre del programa final
PROGRAMA := suma

CC := gcc
CFLAGS := -Wall

# Regla principal: indica qué construir al ejecutar `make`
all: $(PROGRAMA)

# Regla para generar el ejecutable a partir de suma.c
$(PROGRAMA): suma.c
	$(CC) $(CFLAGS) suma.c -o $(PROGRAMA)

# Regla para limpiar los archivos generados
clean:
	rm -f $(PROGRAMA)

.PHONY: all clean
