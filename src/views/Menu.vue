<template>
  <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
    <h1 class="text-2xl font-semibold text-gray-900 mb-6">Menú Principal</h1>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
      <!-- Dashboard -->
      <router-link to="/dashboard" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-orange-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-orange-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M21.21 15.89A10 10 0 1 1 8 2.83"></path>
              <path d="M22 12A10 10 0 0 0 12 2v10z"></path>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Dashboard</h2>
            <p class="text-gray-600 text-center">Visualiza indicadores y gráficos</p>
          </div>
        </div>
      </router-link>

      <!-- POS -->
      <router-link to="/pos" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-blue-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-blue-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <rect x="2" y="3" width="20" height="14" rx="2" ry="2"></rect>
              <line x1="8" y1="21" x2="16" y2="21"></line>
              <line x1="12" y1="17" x2="12" y2="21"></line>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">POS</h2>
            <p class="text-gray-600 text-center">Gestiona ventas y emite comprobantes</p>
          </div>
        </div>
      </router-link>

      <!-- Clientes -->
      <router-link to="/customers" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-purple-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-purple-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
              <circle cx="12" cy="7" r="4"></circle>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Clientes</h2>
            <p class="text-gray-600 text-center">Administra tu cartera de clientes</p>
          </div>
        </div>
      </router-link>

      <!-- Inventario -->
      <router-link to="/inventory" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-green-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-green-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path
                d="M2.97 12.92A2 2 0 0 0 2 14.63v3.24a2 2 0 0 0 .97 1.71l3 1.8a2 2 0 0 0 2.06 0L12 19v-5.5l-5-3-4.03 2.42Z" />
              <path d="m7 16.5-4.74-2.85" />
              <path d="m7 16.5 5-3" />
              <path d="M7 16.5v5.17" />
              <path
                d="M12 13.5V19l3.97 2.38a2 2 0 0 0 2.06 0l3-1.8a2 2 0 0 0 .97-1.71v-3.24a2 2 0 0 0-.97-1.71L17 10.5l-5 3Z" />
              <path d="m17 16.5-5-3" />
              <path d="m17 16.5 4.74-2.85" />
              <path d="M17 16.5v5.17" />
              <path
                d="M7.97 4.42A2 2 0 0 0 7 6.13v4.37l5 3 5-3V6.13a2 2 0 0 0-.97-1.71l-3-1.8a2 2 0 0 0-2.06 0l-3 1.8Z" />
              <path d="M12 8 7.26 5.15" />
              <path d="m12 8 4.74-2.85" />
              <path d="M12 13.5V8" />
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Inventario</h2>
            <p class="text-gray-600 text-center">Gestiona productos, stock y categorías</p>
          </div>
        </div>
      </router-link>

      <!-- Cambios y devoluciones -->
      <router-link to="/returns" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-teal-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-teal-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M21 12a9 9 0 0 0-9-9 9.75 9.75 0 0 0-6.74 2.74L3 8"></path>
              <path d="M3 3v5h5"></path>
              <path d="M3 12a9 9 0 0 0 9 9 9.75 9.75 0 0 0 6.74-2.74L21 16"></path>
              <path d="M16 16h5v5"></path>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Cambios y devoluciones</h2>
            <p class="text-gray-600 text-center">Gestiona cambios y devoluciones de productos</p>
          </div>
        </div>
      </router-link>

      <!-- Documentos -->
      <router-link to="/documents" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-amber-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-amber-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
              <polyline points="14 2 14 8 20 8"></polyline>
              <line x1="16" y1="13" x2="8" y2="13"></line>
              <line x1="16" y1="17" x2="8" y2="17"></line>
              <polyline points="10 9 9 9 8 9"></polyline>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Documentos</h2>
            <p class="text-gray-600 text-center">Gestiona documentos y comprobantes</p>
          </div>
        </div>
      </router-link>

      <!-- Ventas -->
      <router-link to="/sales" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-cyan-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-cyan-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M3 3v18h18"></path>
              <path
                d="M18.4 8.64L18.57 8.8a2 2 0 0 1 0 2.83l-8.49 8.48a2 2 0 0 1-2.83 0l-.17-.17a2 2 0 0 1 0-2.83l8.49-8.48a2 2 0 0 1 2.83 0Z">
              </path>
              <path d="M15 8h5v5"></path>
              <path d="M18 11l-7 7"></path>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Ventas</h2>
            <p class="text-gray-600 text-center">Consulta el historial de ventas</p>
          </div>
        </div>
      </router-link>

      <!-- Descuentos y Promociones -->
      <router-link to="/promotions" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-pink-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-pink-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <line x1="19" y1="5" x2="5" y2="19"></line>
              <circle cx="6.5" cy="6.5" r="2.5"></circle>
              <circle cx="17.5" cy="17.5" r="2.5"></circle>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Descuentos y Promociones</h2>
            <p class="text-gray-600 text-center">Gestiona ofertas y promociones</p>
          </div>
        </div>
      </router-link>

      <!-- Caja (Módulo futuro) -->
      <router-link to="/cashier" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-red-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-red-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <rect x="2" y="5" width="20" height="14" rx="2"></rect>
              <line x1="2" y1="10" x2="22" y2="10"></line>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Caja</h2>
            <p class="text-gray-600 text-center">Apertura y cierre de caja</p>
          </div>
        </div>
      </router-link>

      <!-- Sucursales (Módulo futuro) -->
      <router-link to="/branches" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-indigo-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-indigo-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path>
              <polyline points="9 22 9 12 15 12 15 22"></polyline>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Sucursales</h2>
            <p class="text-gray-600 text-center">Gestión de múltiples locales</p>
          </div>
        </div>
      </router-link>

      <!-- Vales y Tarjetas de Regalo -->
      <router-link to="/vouchers" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-yellow-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-yellow-500 mb-4" viewBox="0 0 24 24"
              fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <rect x="3" y="8" width="18" height="4" rx="1" />
              <path d="M12 8v13" />
              <path d="M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-7" />
              <path d="M7.5 8a2.5 2.5 0 0 1 0-5A4.8 8 0 0 1 12 8a4.8 8 0 0 1 4.5-5 2.5 2.5 0 0 1 0 5" />
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Vales y Tarjetas de Regalo</h2>
            <p class="text-gray-600 text-center">Gestiona vales de consumo y tarjetas de regalo</p>
          </div>
        </div>
      </router-link>

      <!-- Preferencias (antes Configuración) -->
      <router-link to="/preferences" class="block">
        <div
          class="bg-white rounded-lg shadow-md hover:shadow-lg transition-shadow duration-300 p-6 h-full border-l-4 border-gray-500">
          <div class="flex flex-col items-center justify-center h-full text-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16 text-gray-500 mb-4" viewBox="0 0 24 24" fill="none"
              stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <circle cx="12" cy="12" r="3"></circle>
              <path
                d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z">
              </path>
            </svg>
            <h2 class="text-xl font-medium text-gray-900 mb-2">Preferencias</h2>
            <p class="text-gray-600 text-center">Personaliza tu sistema</p>
          </div>
        </div>
      </router-link>
    </div>
  </div>
</template>

<script setup>
</script>
