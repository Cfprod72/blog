---
title: "Contacto"
description: "Hugo, the world's fastest framework for building websites"
date: 2019-02-30
aliases: ["contact"]
author: "Hugo Authors"
---

{{< rawhtml >}}

<div class="content">
    <p class="mb-2">Para contactarnos, favor llene el siguente formulario.</p>
    <form name=contact action="mailto:claudiofarina@cfproducciones.cl" method=post>
    <div class="mb-4">
         <input type=text placeholder="Su nombre" name=name class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Su Mail" name=mail class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <input type=text placeholder="Asunto" name=title class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required>
    </div>
    <div class="mb-4">
        <textarea rows=5 cols=30 placeholder="Mensaje" name=message class="w-full p-4 bg-gray-200 border border-gray-200 focus:outline-none focus:bg-white focus:border-gray-500" required></textarea>
    </div>
    <input type=submit value="Enviar" class="w-full button duration-100 py-2 bg-gray-800 text-white cursor-pointer transition-colors hover:bg-gray-600">
    </form>
</div>
{{< /rawhtml >}}