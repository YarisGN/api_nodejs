# api_nodejs
<h1>Instalación local de paquetes</h1>
<p>Solo se recomienda instalar paquetes localmente para cada proyecto individual.</p>

<p>Para instalar un paquete localmente, navega hasta el directorio de la aplicación de tu sitio (no el directorio /public). 
El comando para instalar un paquete es:</p>
<p>npm install</p>

<h2>Base de datos llamada "library"</h2>

--

CREATE TABLE `books` (
  `id` int(11) NOT NULL,
  `titulo` varchar(100) COLLATE utf8mb4_spanish_ci NOT NULL,
  `autor` varchar(100) COLLATE utf8mb4_spanish_ci NOT NULL,
  `edicion` int(11) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_spanish_ci;

--
-- Volcado de datos para la tabla `books`
--

INSERT INTO `books` (`id`, `titulo`, `autor`, `edicion`) VALUES
(1, 'Los 7 habitos de las personas altamentes efectivas', 'Stephen Hawking', 4),
(3, 'Una breve historia del tiempo', 'Stephen Hawking', 3);

--
-- Índices para tablas volcadas
--

--
-- Indices de la tabla `books`
--
ALTER TABLE `books`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT de las tablas volcadas
--

--
-- AUTO_INCREMENT de la tabla `books`
--
ALTER TABLE `books`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=4;
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
