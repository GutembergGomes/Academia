<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FitTracker Pro - Seu Diário de Treinos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        'primary-dark': '#4B4BBE'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-900 dark:text-white transition-colors duration-300">
    <!-- Header -->
    <header class="bg-primary text-white shadow-lg">
        <div class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <i class="fas fa-dumbbell text-2xl"></i>
                    <h1 class="text-2xl font-bold">FitTracker</h1>
                </div>
                <div class="text-sm">
                    <span id="currentDate"></span>
                </div>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="bg-gray-100 dark:bg-gray-800 border-b border-gray-200 dark:border-gray-700">
        <div class="container mx-auto px-4">
            <div class="flex space-x-8">
                <button class="nav-btn active py-4 px-2 border-b-2 border-primary text-primary font-medium" data-tab="dashboard">
                    <i class="fas fa-chart-line mr-2"></i>Dashboard
                </button>
                <button class="nav-btn py-4 px-2 border-b-2 border-transparent hover:border-gray-300 transition-colors" data-tab="exercises">
                    <i class="fas fa-list mr-2"></i>Exercícios
                </button>
                <button class="nav-btn py-4 px-2 border-b-2 border-transparent hover:border-gray-300 transition-colors" data-tab="workout">
                    <i class="fas fa-plus mr-2"></i>Registrar Treino
                </button>
                <button class="nav-btn py-4 px-2 border-b-2 border-transparent hover:border-gray-300 transition-colors" data-tab="analytics">
                    <i class="fas fa-chart-bar mr-2"></i>Análises
                </button>
                <button class="nav-btn py-4 px-2 border-b-2 border-transparent hover:border-gray-300 transition-colors" data-tab="tools">
                    <i class="fas fa-tools mr-2"></i>Ferramentas
                </button>
                <button class="nav-btn py-4 px-2 border-b-2 border-transparent hover:border-gray-300 transition-colors" data-tab="history">
                    <i class="fas fa-history mr-2"></i>Histórico
                </button>
            </div>
        </div>
    </nav>

    <div class="container mx-auto px-4 py-6">
        <!-- Dashboard Tab -->
        <div id="dashboard" class="tab-content">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                <div class="bg-gradient-to-r from-blue-500 to-blue-600 rounded-lg p-6 text-white">
                    <div class="flex items-center justify-between">
                        <div>
                            <p class="text-blue-100">Treinos Esta Semana</p>
                            <p class="text-3xl font-bold" id="weeklyWorkouts">0</p>
                        </div>
                        <i class="fas fa-calendar-week text-2xl text-blue-200"></i>
                    </div>
                </div>
                <div class="bg-gradient-to-r from-green-500 to-green-600 rounded-lg p-6 text-white">
                    <div class="flex items-center justify-between">
                        <div>
                            <p class="text-green-100">Total de Peso (kg)</p>
                            <p class="text-3xl font-bold" id="totalWeight">0</p>
                        </div>
                        <i class="fas fa-weight-hanging text-2xl text-green-200"></i>
                    </div>
                </div>
                <div class="bg-gradient-to-r from-purple-500 to-purple-600 rounded-lg p-6 text-white">
                    <div class="flex items-center justify-between">
                        <div>
                            <p class="text-purple-100">Tempo Total (min)</p>
                            <p class="text-3xl font-bold" id="totalTime">0</p>
                        </div>
                        <i class="fas fa-clock text-2xl text-purple-200"></i>
                    </div>
                </div>
                <div class="bg-gradient-to-r from-orange-500 to-orange-600 rounded-lg p-6 text-white">
                    <div class="flex items-center justify-between">
                        <div>
                            <p class="text-orange-100">Exercícios Únicos</p>
                            <p class="text-3xl font-bold" id="uniqueExercises">0</p>
                        </div>
                        <i class="fas fa-trophy text-2xl text-orange-200"></i>
                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Últimos Treinos</h3>
                    <div id="recentWorkouts" class="space-y-3">
                        <p class="text-gray-500 dark:text-gray-400">Nenhum treino registrado ainda.</p>
                    </div>
                </div>
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Exercícios Mais Realizados</h3>
                    <div id="popularExercises" class="space-y-3">
                        <p class="text-gray-500 dark:text-gray-400">Nenhum exercício registrado ainda.</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Exercises Tab -->
        <div id="exercises" class="tab-content hidden">
            <div class="mb-6">
                <h2 class="text-3xl font-bold mb-4">Base de Exercícios</h2>
                <div class="mb-4">
                    <input type="text" id="exerciseSearch" placeholder="Buscar exercícios..." 
                           class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary focus:border-transparent bg-white dark:bg-gray-700">
                </div>
                <div class="mb-4">
                    <select id="muscleFilter" class="px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        <option value="">Todos os músculos</option>
                        <option value="peito">Peito</option>
                        <option value="costas">Costas</option>
                        <option value="ombros">Ombros</option>
                        <option value="braços">Braços</option>
                        <option value="pernas">Pernas</option>
                        <option value="core">Core</option>
                    </select>
                </div>
            </div>
            <div id="exerciseList" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Exercises will be populated here -->
            </div>
        </div>

        <!-- Workout Tab -->
        <div id="workout" class="tab-content hidden">
            <div class="max-w-2xl mx-auto">
                <h2 class="text-3xl font-bold mb-6">Registrar Novo Treino</h2>
                
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <form id="workoutForm">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-4">
                            <div>
                                <label class="block text-sm font-medium mb-2">Data do Treino</label>
                                <input type="date" id="workoutDate" required
                                       class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Duração (minutos)</label>
                                <input type="number" id="workoutDuration" required min="1" placeholder="60"
                                       class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                            </div>
                        </div>

                        <div class="mb-6">
                            <h3 class="text-lg font-semibold mb-4">Exercícios</h3>
                            <div id="exerciseEntries">
                                <div class="exercise-entry bg-gray-50 dark:bg-gray-700 p-4 rounded-lg mb-4">
                                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3">
                                        <div>
                                            <label class="block text-sm font-medium mb-1">Exercício</label>
                                            <select class="exercise-select w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-600">
                                                <option value="">Selecione...</option>
                                            </select>
                                        </div>
                                        <div>
                                            <label class="block text-sm font-medium mb-1">Séries</label>
                                            <input type="number" class="sets w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="3">
                                        </div>
                                        <div>
                                            <label class="block text-sm font-medium mb-1">Repetições</label>
                                            <input type="number" class="reps w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="12">
                                        </div>
                                        <div>
                                            <label class="block text-sm font-medium mb-1">Peso (kg)</label>
                                            <input type="number" class="weight w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="0" step="0.5" placeholder="20">
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <button type="button" id="addExercise" class="bg-gray-500 hover:bg-gray-600 text-white px-4 py-2 rounded-lg transition-colors">
                                <i class="fas fa-plus mr-2"></i>Adicionar Exercício
                            </button>
                        </div>

                        <div class="flex justify-end space-x-3">
                            <button type="button" id="clearForm" class="bg-gray-500 hover:bg-gray-600 text-white px-6 py-2 rounded-lg transition-colors">
                                Limpar
                            </button>
                            <button type="submit" class="bg-primary hover:bg-primary-dark text-white px-6 py-2 rounded-lg transition-colors">
                                <i class="fas fa-save mr-2"></i>Salvar Treino
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>

        <!-- Analytics Tab -->
        <div id="analytics" class="tab-content hidden">
            <h2 class="text-3xl font-bold mb-6">Análises e Progressão</h2>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Progresso de Peso por Semana</h3>
                    <canvas id="weightChart" width="400" height="200"></canvas>
                </div>
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Exercícios por Grupo Muscular</h3>
                    <canvas id="muscleChart" width="400" height="200"></canvas>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Frequência de Treinos</h3>
                    <canvas id="frequencyChart" width="400" height="200"></canvas>
                </div>
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">Evolução de Volume</h3>
                    <div id="volumeStats" class="space-y-4">
                        <!-- Volume stats will be populated here -->
                    </div>
                </div>
            </div>

            <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-bold mb-4">Comparação de Exercícios</h3>
                <div class="mb-4">
                    <select id="exerciseCompare" class="px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        <option value="">Selecione um exercício para ver evolução</option>
                    </select>
                </div>
                <canvas id="exerciseProgressChart" width="400" height="200"></canvas>
            </div>
        </div>

        <!-- Tools Tab -->
        <div id="tools" class="tab-content hidden">
            <h2 class="text-3xl font-bold mb-6">Ferramentas e Calculadoras</h2>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                <!-- 1RM Calculator -->
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">
                        <i class="fas fa-calculator mr-2 text-primary"></i>
                        Calculadora 1RM
                    </h3>
                    <p class="text-gray-600 dark:text-gray-400 mb-4">Calcule sua repetição máxima baseada no peso e repetições realizadas.</p>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">Peso utilizado (kg)</label>
                            <input type="number" id="rmWeight" step="0.5" placeholder="100" 
                                   class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Repetições realizadas</label>
                            <input type="number" id="rmReps" min="1" max="20" placeholder="8" 
                                   class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        </div>
                        <button onclick="calculate1RM()" class="w-full bg-primary hover:bg-primary-dark text-white py-2 rounded-lg transition-colors">
                            Calcular 1RM
                        </button>
                        <div id="rmResult" class="hidden mt-4 p-4 bg-green-50 dark:bg-green-900 rounded-lg">
                            <p class="text-green-800 dark:text-green-200 font-medium">Sua repetição máxima estimada:</p>
                            <p class="text-2xl font-bold text-green-600 dark:text-green-400" id="rmValue">-</p>
                        </div>
                    </div>
                </div>

                <!-- BMI Calculator -->
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">
                        <i class="fas fa-weight mr-2 text-primary"></i>
                        Calculadora IMC
                    </h3>
                    <p class="text-gray-600 dark:text-gray-400 mb-4">Calcule seu Índice de Massa Corporal.</p>
                    
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-medium mb-2">Peso (kg)</label>
                            <input type="number" id="bmiWeight" step="0.1" placeholder="70" 
                                   class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-2">Altura (cm)</label>
                            <input type="number" id="bmiHeight" placeholder="175" 
                                   class="w-full px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        </div>
                        <button onclick="calculateBMI()" class="w-full bg-primary hover:bg-primary-dark text-white py-2 rounded-lg transition-colors">
                            Calcular IMC
                        </button>
                        <div id="bmiResult" class="hidden mt-4 p-4 rounded-lg">
                            <p class="font-medium">Seu IMC:</p>
                            <p class="text-2xl font-bold" id="bmiValue">-</p>
                            <p class="text-sm" id="bmiCategory">-</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                <!-- Rest Timer -->
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">
                        <i class="fas fa-stopwatch mr-2 text-primary"></i>
                        Timer de Descanso
                    </h3>
                    <p class="text-gray-600 dark:text-gray-400 mb-4">Cronômetro para intervalos entre séries.</p>
                    
                    <div class="text-center space-y-4">
                        <div class="text-6xl font-bold text-primary" id="timerDisplay">0:00</div>
                        <div class="space-x-2">
                            <button onclick="setTimer(60)" class="bg-gray-500 hover:bg-gray-600 text-white px-4 py-2 rounded-lg">1min</button>
                            <button onclick="setTimer(90)" class="bg-gray-500 hover:bg-gray-600 text-white px-4 py-2 rounded-lg">1:30</button>
                            <button onclick="setTimer(120)" class="bg-gray-500 hover:bg-gray-600 text-white px-4 py-2 rounded-lg">2min</button>
                            <button onclick="setTimer(180)" class="bg-gray-500 hover:bg-gray-600 text-white px-4 py-2 rounded-lg">3min</button>
                        </div>
                        <div class="space-x-2">
                            <button id="timerBtn" onclick="toggleTimer()" class="bg-primary hover:bg-primary-dark text-white px-6 py-2 rounded-lg">
                                <i class="fas fa-play mr-2"></i>Iniciar
                            </button>
                            <button onclick="resetTimer()" class="bg-red-500 hover:bg-red-600 text-white px-6 py-2 rounded-lg">
                                <i class="fas fa-stop mr-2"></i>Parar
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Workout Templates -->
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-4">
                        <i class="fas fa-clipboard-list mr-2 text-primary"></i>
                        Templates de Treino
                    </h3>
                    <p class="text-gray-600 dark:text-gray-400 mb-4">Modelos de treino pré-definidos.</p>
                    
                    <div class="space-y-3">
                        <button onclick="loadTemplate('push')" class="w-full text-left p-3 bg-gray-50 dark:bg-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-600 transition-colors">
                            <div class="font-medium">Push (Empurrar)</div>
                            <div class="text-sm text-gray-600 dark:text-gray-400">Peito, Ombros, Tríceps</div>
                        </button>
                        <button onclick="loadTemplate('pull')" class="w-full text-left p-3 bg-gray-50 dark:bg-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-600 transition-colors">
                            <div class="font-medium">Pull (Puxar)</div>
                            <div class="text-sm text-gray-600 dark:text-gray-400">Costas, Bíceps</div>
                        </button>
                        <button onclick="loadTemplate('legs')" class="w-full text-left p-3 bg-gray-50 dark:bg-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-600 transition-colors">
                            <div class="font-medium">Legs (Pernas)</div>
                            <div class="text-sm text-gray-600 dark:text-gray-400">Quadríceps, Glúteos, Panturrilhas</div>
                        </button>
                        <button onclick="loadTemplate('fullbody')" class="w-full text-left p-3 bg-gray-50 dark:bg-gray-700 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-600 transition-colors">
                            <div class="font-medium">Full Body</div>
                            <div class="text-sm text-gray-600 dark:text-gray-400">Treino completo para corpo todo</div>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Data Export -->
            <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                <h3 class="text-xl font-bold mb-4">
                    <i class="fas fa-download mr-2 text-primary"></i>
                    Exportar Dados
                </h3>
                <p class="text-gray-600 dark:text-gray-400 mb-4">Baixe seus dados de treino em formato JSON para backup.</p>
                <button onclick="exportData()" class="bg-primary hover:bg-primary-dark text-white px-6 py-2 rounded-lg transition-colors">
                    <i class="fas fa-download mr-2"></i>Baixar Dados
                </button>
            </div>
        </div>

        <!-- History Tab -->
        <div id="history" class="tab-content hidden">
            <div class="flex justify-between items-center mb-6">
                <h2 class="text-3xl font-bold">Histórico de Treinos</h2>
                <div class="flex space-x-2">
                    <select id="historyFilter" class="px-4 py-2 text-base border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700">
                        <option value="all">Todos os treinos</option>
                        <option value="week">Última semana</option>
                        <option value="month">Último mês</option>
                        <option value="3months">Últimos 3 meses</option>
                    </select>
                    <button onclick="deleteAllWorkouts()" class="bg-red-500 hover:bg-red-600 text-white px-4 py-2 rounded-lg transition-colors">
                        <i class="fas fa-trash mr-2"></i>Limpar Histórico
                    </button>
                </div>
            </div>
            <div id="workoutHistory" class="space-y-6">
                <p class="text-gray-500 dark:text-gray-400 text-center py-8">Nenhum treino registrado ainda.</p>
            </div>
        </div>
    </div>

    <!-- Exercise Modal -->
    <div id="exerciseModal" class="hidden fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 p-4">
        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-center mb-4">
                    <h3 id="modalTitle" class="text-2xl font-bold"></h3>
                    <button id="closeModal" class="text-gray-500 hover:text-gray-700 dark:hover:text-gray-300">
                        <i class="fas fa-times text-xl"></i>
                    </button>
                </div>
                <div id="modalContent">
                    <!-- Modal content will be populated here -->
                </div>
            </div>
        </div>
    </div>

    <!-- Success Message -->
    <div id="successMessage" class="hidden fixed top-4 right-4 bg-green-500 text-white px-6 py-3 rounded-lg shadow-lg z-50">
        <i class="fas fa-check mr-2"></i>
        <span id="successText">Treino salvo com sucesso!</span>
    </div>

    <script>
        // Dark mode setup
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.documentElement.classList.add('dark');
        }
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
            if (event.matches) {
                document.documentElement.classList.add('dark');
            } else {
                document.documentElement.classList.remove('dark');
            }
        });

        // Data storage (in-memory since localStorage is not available)
        let workouts = [];
        let exerciseDatabase = [
            // Peito
            { name: "Supino Reto", muscle: "peito", instructions: "Deite no banco, segure a barra com pegada um pouco mais larga que os ombros. Desça controladamente até o peito e empurre para cima." },
            { name: "Supino Inclinado", muscle: "peito", instructions: "Similar ao supino reto, mas em banco inclinado (30-45°). Trabalha mais a parte superior do peitoral." },
            { name: "Flexão de Braço", muscle: "peito", instructions: "Em posição de prancha, desça o corpo flexionando os braços até quase tocar o chão, depois empurre para cima." },
            { name: "Crucifixo", muscle: "peito", instructions: "Deitado no banco, segure halteres com braços abertos. Aproxime os halteres acima do peito contraindo o peitoral." },
            
            // Costas
            { name: "Puxada na Polia Alta", muscle: "costas", instructions: "Sentado, puxe a barra em direção ao peito, contraindo as escápulas. Retorne controladamente." },
            { name: "Remada Curvada", muscle: "costas", instructions: "Inclinado para frente, puxe a barra em direção ao abdômen, mantendo as escápulas contraídas." },
            { name: "Barra Fixa", muscle: "costas", instructions: "Pendure na barra e puxe o corpo para cima até o queixo passar da barra. Desça controladamente." },
            { name: "Remada Unilateral", muscle: "costas", instructions: "Apoiado no banco, puxe o halter em direção à cintura, contraindo as costas." },
            
            // Ombros
            { name: "Desenvolvimento", muscle: "ombros", instructions: "Sentado ou em pé, empurre os halteres ou barra acima da cabeça. Desça controladamente." },
            { name: "Elevação Lateral", muscle: "ombros", instructions: "Com halteres nas mãos, eleve os braços lateralmente até a altura dos ombros." },
            { name: "Elevação Frontal", muscle: "ombros", instructions: "Eleve o halter à frente do corpo até a altura dos ombros, alternando os braços." },
            { name: "Crucifixo Inverso", muscle: "ombros", instructions: "Inclinado para frente, abra os braços lateralmente contraindo a parte posterior dos ombros." },
            
            // Braços
            { name: "Rosca Direta", muscle: "braços", instructions: "Com barra ou halteres, flexione os cotovelos contraindo o bíceps. Mantenha os cotovelos fixos." },
            { name: "Tríceps Testa", muscle: "braços", instructions: "Deitado, flexione apenas os antebraços, levando a barra em direção à testa." },
            { name: "Rosca Martelo", muscle: "braços", instructions: "Com halteres em pegada neutra, flexione os cotovelos alternadamente." },
            { name: "Tríceps Pulley", muscle: "braços", instructions: "Na polia alta, empurre a barra para baixo estendendo completamente os braços." },
            
            // Pernas
            { name: "Agachamento", muscle: "pernas", instructions: "Desça flexionando joelhos e quadris como se fosse sentar, mantendo o peito ereto. Suba contraindo glúteos e quadríceps." },
            { name: "Leg Press", muscle: "pernas", instructions: "No aparelho, empurre a plataforma com os pés, estendendo as pernas completamente." },
            { name: "Cadeira Extensora", muscle: "pernas", instructions: "Sentado, estenda as pernas contraindo o quadríceps. Retorne controladamente." },
            { name: "Mesa Flexora", muscle: "pernas", instructions: "Deitado de bruços, flexione as pernas contraindo os posteriores da coxa." },
            { name: "Panturrilha em Pé", muscle: "pernas", instructions: "Na ponta dos pés, eleve o corpo contraindo as panturrilhas. Desça controladamente." },
            
            // Core
            { name: "Abdominal Supra", muscle: "core", instructions: "Deitado, flexione o tronco contraindo o abdômen, sem puxar o pescoço." },
            { name: "Prancha", muscle: "core", instructions: "Mantenha o corpo reto apoiado nos antebraços e pés, contraindo core e glúteos." },
            { name: "Abdominal Oblíquo", muscle: "core", instructions: "Deitado de lado, flexione o tronco lateralmente contraindo os oblíquos." },
            { name: "Mountain Climber", muscle: "core", instructions: "Em posição de prancha, alterne levando os joelhos em direção ao peito rapidamente." }
        ];

        // Initialize app
        document.addEventListener('DOMContentLoaded', function() {
            updateCurrentDate();
            populateExerciseSelects();
            populateExerciseList();
            updateDashboard();
            
            // Set default date to today
            document.getElementById('workoutDate').value = new Date().toISOString().split('T')[0];
        });

        // Update current date
        function updateCurrentDate() {
            const now = new Date();
            const options = { 
                weekday: 'long', 
                year: 'numeric', 
                month: 'long', 
                day: 'numeric' 
            };
            document.getElementById('currentDate').textContent = 
                now.toLocaleDateString('pt-BR', options);
        }

        // Tab navigation
        document.querySelectorAll('.nav-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                const targetTab = this.dataset.tab;
                
                // Update active button
                document.querySelectorAll('.nav-btn').forEach(b => {
                    b.classList.remove('active', 'border-primary', 'text-primary');
                    b.classList.add('border-transparent');
                });
                this.classList.add('active', 'border-primary', 'text-primary');
                this.classList.remove('border-transparent');
                
                // Show target tab
                document.querySelectorAll('.tab-content').forEach(tab => {
                    tab.classList.add('hidden');
                });
                document.getElementById(targetTab).classList.remove('hidden');
                
                // Update dashboard when switching to it
                if (targetTab === 'dashboard') {
                    updateDashboard();
                }
            });
        });

        // Populate exercise selects
        function populateExerciseSelects() {
            const selects = document.querySelectorAll('.exercise-select');
            selects.forEach(select => {
                select.innerHTML = '<option value="">Selecione...</option>';
                exerciseDatabase.forEach(exercise => {
                    const option = document.createElement('option');
                    option.value = exercise.name;
                    option.textContent = exercise.name;
                    select.appendChild(option);
                });
            });
        }

        // Populate exercise list
        function populateExerciseList() {
            const container = document.getElementById('exerciseList');
            container.innerHTML = '';
            
            exerciseDatabase.forEach(exercise => {
                const card = document.createElement('div');
                card.className = 'bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow cursor-pointer';
                card.innerHTML = `
                    <div class="flex items-center justify-between mb-3">
                        <h3 class="text-lg font-semibold">${exercise.name}</h3>
                        <span class="bg-primary text-white px-2 py-1 rounded text-sm capitalize">${exercise.muscle}</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-400 text-sm mb-4">${exercise.instructions.substring(0, 100)}...</p>
                    <button class="text-primary hover:text-primary-dark font-medium" onclick="showExerciseModal('${exercise.name}')">
                        Ver tutorial completo <i class="fas fa-arrow-right ml-1"></i>
                    </button>
                `;
                container.appendChild(card);
            });
        }

        // Exercise search and filter
        document.getElementById('exerciseSearch').addEventListener('input', filterExercises);
        document.getElementById('muscleFilter').addEventListener('change', filterExercises);

        function filterExercises() {
            const searchTerm = document.getElementById('exerciseSearch').value.toLowerCase();
            const muscleFilter = document.getElementById('muscleFilter').value;
            
            const filtered = exerciseDatabase.filter(exercise => {
                const matchesSearch = exercise.name.toLowerCase().includes(searchTerm) ||
                                    exercise.instructions.toLowerCase().includes(searchTerm);
                const matchesMuscle = !muscleFilter || exercise.muscle === muscleFilter;
                return matchesSearch && matchesMuscle;
            });
            
            const container = document.getElementById('exerciseList');
            container.innerHTML = '';
            
            filtered.forEach(exercise => {
                const card = document.createElement('div');
                card.className = 'bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6 hover:shadow-xl transition-shadow cursor-pointer';
                card.innerHTML = `
                    <div class="flex items-center justify-between mb-3">
                        <h3 class="text-lg font-semibold">${exercise.name}</h3>
                        <span class="bg-primary text-white px-2 py-1 rounded text-sm capitalize">${exercise.muscle}</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-400 text-sm mb-4">${exercise.instructions.substring(0, 100)}...</p>
                    <button class="text-primary hover:text-primary-dark font-medium" onclick="showExerciseModal('${exercise.name}')">
                        Ver tutorial completo <i class="fas fa-arrow-right ml-1"></i>
                    </button>
                `;
                container.appendChild(card);
            });
        }

        // Show exercise modal
        function showExerciseModal(exerciseName) {
            const exercise = exerciseDatabase.find(ex => ex.name === exerciseName);
            if (!exercise) return;
            
            document.getElementById('modalTitle').textContent = exercise.name;
            document.getElementById('modalContent').innerHTML = `
                <div class="mb-4">
                    <span class="bg-primary text-white px-3 py-1 rounded-full text-sm capitalize">${exercise.muscle}</span>
                </div>
                <div class="prose dark:prose-invert max-w-none">
                    <h4 class="text-lg font-semibold mb-3">Como executar:</h4>
                    <p class="text-gray-700 dark:text-gray-300 leading-relaxed">${exercise.instructions}</p>
                </div>
            `;
            document.getElementById('exerciseModal').classList.remove('hidden');
        }

        // Close modal
        document.getElementById('closeModal').addEventListener('click', function() {
            document.getElementById('exerciseModal').classList.add('hidden');
        });

        // Add exercise entry
        document.getElementById('addExercise').addEventListener('click', function() {
            const container = document.getElementById('exerciseEntries');
            const newEntry = document.createElement('div');
            newEntry.className = 'exercise-entry bg-gray-50 dark:bg-gray-700 p-4 rounded-lg mb-4';
            newEntry.innerHTML = `
                <div class="flex justify-between items-center mb-3">
                    <span class="font-medium">Exercício ${container.children.length + 1}</span>
                    <button type="button" class="remove-exercise text-red-500 hover:text-red-700" onclick="removeExercise(this)">
                        <i class="fas fa-trash"></i>
                    </button>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3">
                    <div>
                        <label class="block text-sm font-medium mb-1">Exercício</label>
                        <select class="exercise-select w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-600">
                            <option value="">Selecione...</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium mb-1">Séries</label>
                        <input type="number" class="sets w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="3">
                    </div>
                    <div>
                        <label class="block text-sm font-medium mb-1">Repetições</label>
                        <input type="number" class="reps w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="12">
                    </div>
                    <div>
                        <label class="block text-sm font-medium mb-1">Peso (kg)</label>
                        <input type="number" class="weight w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="0" step="0.5" placeholder="20">
                    </div>
                </div>
            `;
            container.appendChild(newEntry);
            
            // Populate the new select
            const newSelect = newEntry.querySelector('.exercise-select');
            exerciseDatabase.forEach(exercise => {
                const option = document.createElement('option');
                option.value = exercise.name;
                option.textContent = exercise.name;
                newSelect.appendChild(option);
            });
        });

        function removeExercise(button) {
            button.closest('.exercise-entry').remove();
        }

        // Workout form submission
        document.getElementById('workoutForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const date = document.getElementById('workoutDate').value;
            const duration = parseInt(document.getElementById('workoutDuration').value);
            
            const exercises = [];
            const entries = document.querySelectorAll('.exercise-entry');
            
            entries.forEach(entry => {
                const exercise = entry.querySelector('.exercise-select').value;
                const sets = parseInt(entry.querySelector('.sets').value);
                const reps = parseInt(entry.querySelector('.reps').value);
                const weight = parseFloat(entry.querySelector('.weight').value) || 0;
                
                if (exercise && sets && reps) {
                    exercises.push({ exercise, sets, reps, weight });
                }
            });
            
            if (exercises.length === 0) {
                showCustomAlert('Adicione pelo menos um exercício ao treino!');
                return;
            }
            
            const workout = {
                id: Date.now(),
                date,
                duration,
                exercises,
                totalWeight: exercises.reduce((sum, ex) => sum + (ex.weight * ex.sets * ex.reps), 0)
            };
            
            workouts.push(workout);
            
            showSuccessMessage('Treino salvo com sucesso!');
            clearWorkoutForm();
            updateDashboard();
            updateWorkoutHistory();
        });

        // Clear workout form
        document.getElementById('clearForm').addEventListener('click', clearWorkoutForm);

        function clearWorkoutForm() {
            document.getElementById('workoutForm').reset();
            document.getElementById('workoutDate').value = new Date().toISOString().split('T')[0];
            
            const container = document.getElementById('exerciseEntries');
            container.innerHTML = `
                <div class="exercise-entry bg-gray-50 dark:bg-gray-700 p-4 rounded-lg mb-4">
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3">
                        <div>
                            <label class="block text-sm font-medium mb-1">Exercício</label>
                            <select class="exercise-select w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-600">
                                <option value="">Selecione...</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Séries</label>
                            <input type="number" class="sets w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="3">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Repetições</label>
                            <input type="number" class="reps w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" placeholder="12">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Peso (kg)</label>
                            <input type="number" class="weight w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="0" step="0.5" placeholder="20">
                        </div>
                    </div>
                </div>
            `;
            populateExerciseSelects();
        }

        // Update dashboard
        function updateDashboard() {
            const now = new Date();
            const weekStart = new Date(now.setDate(now.getDate() - now.getDay()));
            const weeklyWorkouts = workouts.filter(w => new Date(w.date) >= weekStart).length;
            
            const totalWeight = workouts.reduce((sum, w) => sum + w.totalWeight, 0);
            const totalTime = workouts.reduce((sum, w) => sum + w.duration, 0);
            
            const uniqueExercises = new Set();
            workouts.forEach(w => {
                w.exercises.forEach(e => uniqueExercises.add(e.exercise));
            });
            
            document.getElementById('weeklyWorkouts').textContent = weeklyWorkouts;
            document.getElementById('totalWeight').textContent = totalWeight.toFixed(1);
            document.getElementById('totalTime').textContent = totalTime;
            document.getElementById('uniqueExercises').textContent = uniqueExercises.size;
            
            // Recent workouts
            const recentContainer = document.getElementById('recentWorkouts');
            const recentWorkouts = workouts.slice(-5).reverse();
            
            if (recentWorkouts.length === 0) {
                recentContainer.innerHTML = '<p class="text-gray-500 dark:text-gray-400">Nenhum treino registrado ainda.</p>';
            } else {
                recentContainer.innerHTML = recentWorkouts.map(workout => `
                    <div class="flex justify-between items-center p-3 bg-gray-50 dark:bg-gray-700 rounded">
                        <div>
                            <p class="font-medium">${new Date(workout.date).toLocaleDateString('pt-BR')}</p>
                            <p class="text-sm text-gray-600 dark:text-gray-400">${workout.exercises.length} exercícios • ${workout.duration}min</p>
                        </div>
                        <div class="text-right">
                            <p class="font-medium text-primary">${workout.totalWeight.toFixed(1)}kg</p>
                        </div>
                    </div>
                `).join('');
            }
            
            // Popular exercises
            const exerciseCount = {};
            workouts.forEach(w => {
                w.exercises.forEach(e => {
                    exerciseCount[e.exercise] = (exerciseCount[e.exercise] || 0) + 1;
                });
            });
            
            const popularContainer = document.getElementById('popularExercises');
            const sortedExercises = Object.entries(exerciseCount)
                .sort((a, b) => b[1] - a[1])
                .slice(0, 5);
            
            if (sortedExercises.length === 0) {
                popularContainer.innerHTML = '<p class="text-gray-500 dark:text-gray-400">Nenhum exercício registrado ainda.</p>';
            } else {
                popularContainer.innerHTML = sortedExercises.map(([exercise, count]) => `
                    <div class="flex justify-between items-center p-3 bg-gray-50 dark:bg-gray-700 rounded">
                        <p class="font-medium">${exercise}</p>
                        <span class="bg-primary text-white px-2 py-1 rounded text-sm">${count}x</span>
                    </div>
                `).join('');
            }
        }

        // Update workout history
        function updateWorkoutHistory() {
            const container = document.getElementById('workoutHistory');
            
            if (workouts.length === 0) {
                container.innerHTML = '<p class="text-gray-500 dark:text-gray-400 text-center py-8">Nenhum treino registrado ainda.</p>';
                return;
            }
            
            const sortedWorkouts = workouts.sort((a, b) => new Date(b.date) - new Date(a.date));
            
            container.innerHTML = sortedWorkouts.map(workout => `
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <div class="flex justify-between items-center mb-4">
                        <h3 class="text-xl font-bold">${new Date(workout.date).toLocaleDateString('pt-BR', { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' })}</h3>
                        <div class="text-right">
                            <p class="text-sm text-gray-600 dark:text-gray-400">Duração: ${workout.duration} min</p>
                            <p class="font-medium text-primary">Total: ${workout.totalWeight.toFixed(1)}kg</p>
                        </div>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                        ${workout.exercises.map(exercise => `
                            <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded">
                                <h4 class="font-medium mb-2">${exercise.exercise}</h4>
                                <p class="text-sm text-gray-600 dark:text-gray-400">
                                    ${exercise.sets} séries × ${exercise.reps} reps
                                    ${exercise.weight > 0 ? ` @ ${exercise.weight}kg` : ''}
                                </p>
                            </div>
                        `).join('')}
                    </div>
                </div>
            `).join('');
        }

        // Show success message
        function showSuccessMessage(message) {
            document.getElementById('successText').textContent = message;
            const successEl = document.getElementById('successMessage');
            successEl.classList.remove('hidden');
            setTimeout(() => {
                successEl.classList.add('hidden');
            }, 3000);
        }

        // Timer functionality
        let timerInterval = null;
        let timerSeconds = 0;
        let isTimerRunning = false;

        function setTimer(seconds) {
            timerSeconds = seconds;
            updateTimerDisplay();
        }

        function toggleTimer() {
            if (isTimerRunning) {
                pauseTimer();
            } else {
                startTimer();
            }
        }

        function startTimer() {
            if (timerSeconds === 0) {
                timerSeconds = 120; // Default 2 minutes
            }
            
            isTimerRunning = true;
            document.getElementById('timerBtn').innerHTML = '<i class="fas fa-pause mr-2"></i>Pausar';
            
            timerInterval = setInterval(() => {
                timerSeconds--;
                updateTimerDisplay();
                
                if (timerSeconds <= 0) {
                    resetTimer();
                    showSuccessMessage('Tempo de descanso finalizado!');
                }
            }, 1000);
        }

        function pauseTimer() {
            isTimerRunning = false;
            clearInterval(timerInterval);
            document.getElementById('timerBtn').innerHTML = '<i class="fas fa-play mr-2"></i>Retomar';
        }

        function resetTimer() {
            isTimerRunning = false;
            clearInterval(timerInterval);
            timerSeconds = 0;
            updateTimerDisplay();
            document.getElementById('timerBtn').innerHTML = '<i class="fas fa-play mr-2"></i>Iniciar';
        }

        function updateTimerDisplay() {
            const minutes = Math.floor(timerSeconds / 60);
            const seconds = timerSeconds % 60;
            document.getElementById('timerDisplay').textContent = 
                `${minutes}:${seconds.toString().padStart(2, '0')}`;
        }

        // 1RM Calculator
        function calculate1RM() {
            const weight = parseFloat(document.getElementById('rmWeight').value);
            const reps = parseInt(document.getElementById('rmReps').value);
            
            if (!weight || !reps || reps < 1 || reps > 20) {
                showCustomAlert('Por favor, insira valores válidos (peso > 0 e repetições entre 1-20)');
                return;
            }
            
            // Brzycki formula: 1RM = weight × (36 / (37 - reps))
            const oneRM = weight * (36 / (37 - reps));
            
            document.getElementById('rmValue').textContent = `${oneRM.toFixed(1)}kg`;
            document.getElementById('rmResult').classList.remove('hidden');
        }

        // BMI Calculator
        function calculateBMI() {
            const weight = parseFloat(document.getElementById('bmiWeight').value);
            const height = parseFloat(document.getElementById('bmiHeight').value);
            
            if (!weight || !height || weight <= 0 || height <= 0) {
                showCustomAlert('Por favor, insira valores válidos para peso e altura');
                return;
            }
            
            const heightInMeters = height / 100;
            const bmi = weight / (heightInMeters * heightInMeters);
            
            let category, color;
            if (bmi < 18.5) {
                category = 'Abaixo do peso';
                color = 'text-blue-600 dark:text-blue-400';
            } else if (bmi < 25) {
                category = 'Peso normal';
                color = 'text-green-600 dark:text-green-400';
            } else if (bmi < 30) {
                category = 'Sobrepeso';
                color = 'text-yellow-600 dark:text-yellow-400';
            } else {
                category = 'Obesidade';
                color = 'text-red-600 dark:text-red-400';
            }
            
            document.getElementById('bmiValue').textContent = bmi.toFixed(1);
            document.getElementById('bmiValue').className = `text-2xl font-bold ${color}`;
            document.getElementById('bmiCategory').textContent = category;
            document.getElementById('bmiCategory').className = `text-sm ${color}`;
            document.getElementById('bmiResult').classList.remove('hidden');
            
            // Set background color based on category
            const resultDiv = document.getElementById('bmiResult');
            if (bmi < 18.5) {
                resultDiv.className = 'mt-4 p-4 bg-blue-50 dark:bg-blue-900 rounded-lg';
            } else if (bmi < 25) {
                resultDiv.className = 'mt-4 p-4 bg-green-50 dark:bg-green-900 rounded-lg';
            } else if (bmi < 30) {
                resultDiv.className = 'mt-4 p-4 bg-yellow-50 dark:bg-yellow-900 rounded-lg';
            } else {
                resultDiv.className = 'mt-4 p-4 bg-red-50 dark:bg-red-900 rounded-lg';
            }
        }

        // Workout Templates
        const workoutTemplates = {
            push: [
                { exercise: "Supino Reto", sets: 4, reps: 8, weight: 60 },
                { exercise: "Supino Inclinado", sets: 3, reps: 10, weight: 50 },
                { exercise: "Desenvolvimento", sets: 3, reps: 12, weight: 30 },
                { exercise: "Elevação Lateral", sets: 3, reps: 15, weight: 10 },
                { exercise: "Tríceps Pulley", sets: 3, reps: 12, weight: 25 }
            ],
            pull: [
                { exercise: "Puxada na Polia Alta", sets: 4, reps: 8, weight: 50 },
                { exercise: "Remada Curvada", sets: 3, reps: 10, weight: 40 },
                { exercise: "Barra Fixa", sets: 3, reps: 8, weight: 0 },
                { exercise: "Rosca Direta", sets: 3, reps: 12, weight: 20 },
                { exercise: "Rosca Martelo", sets: 3, reps: 12, weight: 15 }
            ],
            legs: [
                { exercise: "Agachamento", sets: 4, reps: 10, weight: 70 },
                { exercise: "Leg Press", sets: 3, reps: 12, weight: 150 },
                { exercise: "Cadeira Extensora", sets: 3, reps: 15, weight: 40 },
                { exercise: "Mesa Flexora", sets: 3, reps: 12, weight: 35 },
                { exercise: "Panturrilha em Pé", sets: 4, reps: 20, weight: 60 }
            ],
            fullbody: [
                { exercise: "Agachamento", sets: 3, reps: 10, weight: 60 },
                { exercise: "Supino Reto", sets: 3, reps: 10, weight: 50 },
                { exercise: "Puxada na Polia Alta", sets: 3, reps: 10, weight: 45 },
                { exercise: "Desenvolvimento", sets: 3, reps: 12, weight: 25 },
                { exercise: "Prancha", sets: 3, reps: 30, weight: 0 }
            ]
        };

        function loadTemplate(templateName) {
            const template = workoutTemplates[templateName];
            if (!template) return;
            
            // Switch to workout tab
            document.querySelector('[data-tab="workout"]').click();
            
            // Clear existing entries
            const container = document.getElementById('exerciseEntries');
            container.innerHTML = '';
            
            // Add template exercises
            template.forEach((exerciseData, index) => {
                const newEntry = document.createElement('div');
                newEntry.className = 'exercise-entry bg-gray-50 dark:bg-gray-700 p-4 rounded-lg mb-4';
                newEntry.innerHTML = `
                    <div class="flex justify-between items-center mb-3">
                        <span class="font-medium">Exercício ${index + 1}</span>
                        ${index > 0 ? '<button type="button" class="remove-exercise text-red-500 hover:text-red-700" onclick="removeExercise(this)"><i class="fas fa-trash"></i></button>' : ''}
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3">
                        <div>
                            <label class="block text-sm font-medium mb-1">Exercício</label>
                            <select class="exercise-select w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-600">
                                <option value="">Selecione...</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Séries</label>
                            <input type="number" class="sets w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" value="${exerciseData.sets}">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Repetições</label>
                            <input type="number" class="reps w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="1" value="${exerciseData.reps}">
                        </div>
                        <div>
                            <label class="block text-sm font-medium mb-1">Peso (kg)</label>
                            <input type="number" class="weight w-full px-3 py-2 text-base border border-gray-300 dark:border-gray-600 rounded focus:ring-2 focus:ring-primary bg-white dark:bg-gray-700" min="0" step="0.5" value="${exerciseData.weight}">
                        </div>
                    </div>
                `;
                container.appendChild(newEntry);
                
                // Populate and select the exercise
                const newSelect = newEntry.querySelector('.exercise-select');
                exerciseDatabase.forEach(exercise => {
                    const option = document.createElement('option');
                    option.value = exercise.name;
                    option.textContent = exercise.name;
                    if (exercise.name === exerciseData.exercise) {
                        option.selected = true;
                    }
                    newSelect.appendChild(option);
                });
            });
            
            showSuccessMessage(`Template "${templateName}" carregado com sucesso!`);
        }

        // Data Export
        function exportData() {
            const data = {
                workouts: workouts,
                exportDate: new Date().toISOString(),
                version: '1.0'
            };
            
            const blob = new Blob([JSON.stringify(data, null, 2)], { type: 'application/json' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `fittracker-backup-${new Date().toISOString().split('T')[0]}.json`;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            showSuccessMessage('Dados exportados com sucesso!');
        }

        // History Filter
        document.getElementById('historyFilter').addEventListener('change', function() {
            const filter = this.value;
            let filteredWorkouts = [...workouts];
            
            const now = new Date();
            
            switch(filter) {
                case 'week':
                    const weekAgo = new Date(now.getTime() - 7 * 24 * 60 * 60 * 1000);
                    filteredWorkouts = workouts.filter(w => new Date(w.date) >= weekAgo);
                    break;
                case 'month':
                    const monthAgo = new Date(now.getFullYear(), now.getMonth() - 1, now.getDate());
                    filteredWorkouts = workouts.filter(w => new Date(w.date) >= monthAgo);
                    break;
                case '3months':
                    const threeMonthsAgo = new Date(now.getFullYear(), now.getMonth() - 3, now.getDate());
                    filteredWorkouts = workouts.filter(w => new Date(w.date) >= threeMonthsAgo);
                    break;
            }
            
            displayFilteredWorkouts(filteredWorkouts);
        });

        function displayFilteredWorkouts(filteredWorkouts) {
            const container = document.getElementById('workoutHistory');
            
            if (filteredWorkouts.length === 0) {
                container.innerHTML = '<p class="text-gray-500 dark:text-gray-400 text-center py-8">Nenhum treino encontrado para o período selecionado.</p>';
                return;
            }
            
            const sortedWorkouts = filteredWorkouts.sort((a, b) => new Date(b.date) - new Date(a.date));
            
            container.innerHTML = sortedWorkouts.map(workout => `
                <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6">
                    <div class="flex justify-between items-center mb-4">
                        <h3 class="text-xl font-bold">${new Date(workout.date).toLocaleDateString('pt-BR', { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' })}</h3>
                        <div class="text-right">
                            <p class="text-sm text-gray-600 dark:text-gray-400">Duração: ${workout.duration} min</p>
                            <p class="font-medium text-primary">Total: ${workout.totalWeight.toFixed(1)}kg</p>
                            <button onclick="deleteWorkout(${workout.id})" class="text-red-500 hover:text-red-700 text-sm mt-1">
                                <i class="fas fa-trash mr-1"></i>Excluir
                            </button>
                        </div>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                        ${workout.exercises.map(exercise => `
                            <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded">
                                <h4 class="font-medium mb-2">${exercise.exercise}</h4>
                                <p class="text-sm text-gray-600 dark:text-gray-400">
                                    ${exercise.sets} séries × ${exercise.reps} reps
                                    ${exercise.weight > 0 ? ` @ ${exercise.weight}kg` : ''}
                                </p>
                            </div>
                        `).join('')}
                    </div>
                </div>
            `).join('');
        }

        // Delete functions
        function deleteWorkout(workoutId) {
            showConfirmDialog('Tem certeza que deseja excluir este treino?', () => {
                workouts = workouts.filter(w => w.id !== workoutId);
                updateWorkoutHistory();
                updateDashboard();
                showSuccessMessage('Treino excluído com sucesso!');
            });
        }

        function deleteAllWorkouts() {
            if (workouts.length === 0) {
                showCustomAlert('Não há treinos para excluir.');
                return;
            }
            
            showConfirmDialog('Tem certeza que deseja excluir TODOS os treinos? Esta ação não pode ser desfeita.', () => {
                workouts = [];
                updateWorkoutHistory();
                updateDashboard();
                showSuccessMessage('Todos os treinos foram excluídos!');
            });
        }

        function showConfirmDialog(message, onConfirm) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
            modal.innerHTML = `
                <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                    <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                    <div class="flex justify-end space-x-3">
                        <button class="px-4 py-2 text-gray-600 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-700 rounded" onclick="this.closest('.fixed').remove()">Cancelar</button>
                        <button class="px-4 py-2 bg-red-500 text-white hover:bg-red-600 rounded" onclick="this.closest('.fixed').remove(); (${onConfirm})()">Confirmar</button>
                    </div>
                </div>
            `;
            document.body.appendChild(modal);
        }

        // Analytics Charts
        let weightChart, muscleChart, frequencyChart, exerciseProgressChart;

        // Tab navigation enhancement for analytics
        document.querySelectorAll('.nav-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                const targetTab = this.dataset.tab;
                
                if (targetTab === 'analytics') {
                    setTimeout(() => {
                        updateAnalytics();
                    }, 100);
                }
            });
        });

        function updateAnalytics() {
            if (workouts.length === 0) {
                // Show empty state for charts
                updateEmptyAnalytics();
                return;
            }
            
            updateWeightChart();
            updateMuscleChart();
            updateFrequencyChart();
            updateVolumeStats();
            updateExerciseCompare();
        }

        function updateEmptyAnalytics() {
            // Destroy existing charts
            [weightChart, muscleChart, frequencyChart, exerciseProgressChart].forEach(chart => {
                if (chart) chart.destroy();
            });
            
            // Show empty message
            document.getElementById('volumeStats').innerHTML = '<p class="text-gray-500 dark:text-gray-400">Registre alguns treinos para ver as análises.</p>';
        }

        function updateWeightChart() {
            const ctx = document.getElementById('weightChart').getContext('2d');
            
            // Group workouts by week
            const weeklyData = {};
            workouts.forEach(workout => {
                const date = new Date(workout.date);
                const weekStart = new Date(date.setDate(date.getDate() - date.getDay()));
                const weekKey = weekStart.toISOString().split('T')[0];
                
                if (!weeklyData[weekKey]) {
                    weeklyData[weekKey] = 0;
                }
                weeklyData[weekKey] += workout.totalWeight;
            });
            
            const labels = Object.keys(weeklyData).sort().map(date => 
                new Date(date).toLocaleDateString('pt-BR', { month: 'short', day: 'numeric' })
            );
            const data = Object.keys(weeklyData).sort().map(date => weeklyData[date]);
            
            if (weightChart) weightChart.destroy();
            
            weightChart = new Chart(ctx, {
                type: 'line',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Peso Total (kg)',
                        data: data,
                        borderColor: '#5D5CDE',
                        backgroundColor: 'rgba(93, 92, 222, 0.1)',
                        tension: 0.1,
                        fill: true
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        legend: {
                            display: false
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true
                        }
                    }
                }
            });
        }

        function updateMuscleChart() {
            const ctx = document.getElementById('muscleChart').getContext('2d');
            
            const muscleCount = {};
            workouts.forEach(workout => {
                workout.exercises.forEach(exercise => {
                    const exerciseData = exerciseDatabase.find(ex => ex.name === exercise.exercise);
                    if (exerciseData) {
                        const muscle = exerciseData.muscle;
                        muscleCount[muscle] = (muscleCount[muscle] || 0) + 1;
                    }
                });
            });
            
            const labels = Object.keys(muscleCount);
            const data = Object.values(muscleCount);
            const colors = ['#5D5CDE', '#10B981', '#F59E0B', '#EF4444', '#8B5CF6', '#06B6D4'];
            
            if (muscleChart) muscleChart.destroy();
            
            muscleChart = new Chart(ctx, {
                type: 'doughnut',
                data: {
                    labels: labels.map(label => label.charAt(0).toUpperCase() + label.slice(1)),
                    datasets: [{
                        data: data,
                        backgroundColor: colors.slice(0, labels.length)
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        legend: {
                            position: 'bottom'
                        }
                    }
                }
            });
        }

        function updateFrequencyChart() {
            const ctx = document.getElementById('frequencyChart').getContext('2d');
            
            // Group workouts by day of week
            const dayCount = [0, 0, 0, 0, 0, 0, 0]; // Sun to Sat
            workouts.forEach(workout => {
                const day = new Date(workout.date).getDay();
                dayCount[day]++;
            });
            
            const labels = ['Dom', 'Seg', 'Ter', 'Qua', 'Qui', 'Sex', 'Sáb'];
            
            if (frequencyChart) frequencyChart.destroy();
            
            frequencyChart = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Treinos',
                        data: dayCount,
                        backgroundColor: '#5D5CDE',
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        legend: {
                            display: false
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                                stepSize: 1
                            }
                        }
                    }
                }
            });
        }

        function updateVolumeStats() {
            const container = document.getElementById('volumeStats');
            
            if (workouts.length === 0) {
                container.innerHTML = '<p class="text-gray-500 dark:text-gray-400">Nenhum treino registrado ainda.</p>';
                return;
            }
            
            // Calculate volume stats
            const totalVolume = workouts.reduce((sum, w) => sum + w.totalWeight, 0);
            const avgVolume = totalVolume / workouts.length;
            const maxVolume = Math.max(...workouts.map(w => w.totalWeight));
            const recentVolume = workouts.slice(-5).reduce((sum, w) => sum + w.totalWeight, 0) / Math.min(5, workouts.length);
            
            container.innerHTML = `
                <div class="grid grid-cols-2 gap-4">
                    <div class="text-center p-4 bg-gray-50 dark:bg-gray-700 rounded-lg">
                        <p class="text-2xl font-bold text-primary">${totalVolume.toFixed(1)}kg</p>
                        <p class="text-sm text-gray-600 dark:text-gray-400">Volume Total</p>
                    </div>
                    <div class="text-center p-4 bg-gray-50 dark:bg-gray-700 rounded-lg">
                        <p class="text-2xl font-bold text-green-600">${avgVolume.toFixed(1)}kg</p>
                        <p class="text-sm text-gray-600 dark:text-gray-400">Média por Treino</p>
                    </div>
                    <div class="text-center p-4 bg-gray-50 dark:bg-gray-700 rounded-lg">
                        <p class="text-2xl font-bold text-orange-600">${maxVolume.toFixed(1)}kg</p>
                        <p class="text-sm text-gray-600 dark:text-gray-400">Recorde</p>
                    </div>
                    <div class="text-center p-4 bg-gray-50 dark:bg-gray-700 rounded-lg">
                        <p class="text-2xl font-bold text-purple-600">${recentVolume.toFixed(1)}kg</p>
                        <p class="text-sm text-gray-600 dark:text-gray-400">Média Recente</p>
                    </div>
                </div>
            `;
        }

        function updateExerciseCompare() {
            const select = document.getElementById('exerciseCompare');
            
            // Get unique exercises
            const exercises = new Set();
            workouts.forEach(workout => {
                workout.exercises.forEach(exercise => {
                    exercises.add(exercise.exercise);
                });
            });
            
            // Populate select
            select.innerHTML = '<option value="">Selecione um exercício para ver evolução</option>';
            Array.from(exercises).sort().forEach(exercise => {
                const option = document.createElement('option');
                option.value = exercise;
                option.textContent = exercise;
                select.appendChild(option);
            });
            
            // Add change listener
            select.onchange = function() {
                if (this.value) {
                    updateExerciseProgressChart(this.value);
                }
            };
        }

        function updateExerciseProgressChart(exerciseName) {
            const ctx = document.getElementById('exerciseProgressChart').getContext('2d');
            
            // Get exercise data over time
            const exerciseData = [];
            workouts.forEach(workout => {
                workout.exercises.forEach(exercise => {
                    if (exercise.exercise === exerciseName) {
                        exerciseData.push({
                            date: workout.date,
                            weight: exercise.weight,
                            volume: exercise.weight * exercise.sets * exercise.reps
                        });
                    }
                });
            });
            
            // Sort by date
            exerciseData.sort((a, b) => new Date(a.date) - new Date(b.date));
            
            const labels = exerciseData.map(data => 
                new Date(data.date).toLocaleDateString('pt-BR', { month: 'short', day: 'numeric' })
            );
            
            if (exerciseProgressChart) exerciseProgressChart.destroy();
            
            exerciseProgressChart = new Chart(ctx, {
                type: 'line',
                data: {
                    labels: labels,
                    datasets: [{
                        label: 'Peso (kg)',
                        data: exerciseData.map(data => data.weight),
                        borderColor: '#5D5CDE',
                        backgroundColor: 'rgba(93, 92, 222, 0.1)',
                        yAxisID: 'y'
                    }, {
                        label: 'Volume Total (kg)',
                        data: exerciseData.map(data => data.volume),
                        borderColor: '#10B981',
                        backgroundColor: 'rgba(16, 185, 129, 0.1)',
                        yAxisID: 'y1'
                    }]
                },
                options: {
                    responsive: true,
                    plugins: {
                        title: {
                            display: true,
                            text: `Progresso: ${exerciseName}`
                        }
                    },
                    scales: {
                        y: {
                            type: 'linear',
                            display: true,
                            position: 'left',
                            title: {
                                display: true,
                                text: 'Peso (kg)'
                            }
                        },
                        y1: {
                            type: 'linear',
                            display: true,
                            position: 'right',
                            title: {
                                display: true,
                                text: 'Volume (kg)'
                            },
                            grid: {
                                drawOnChartArea: false,
                            },
                        }
                    }
                }
            });
        }

        // Custom alert function
        function showCustomAlert(message) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50';
            modal.innerHTML = `
                <div class="bg-white dark:bg-gray-800 p-6 rounded-lg shadow-lg max-w-sm w-full mx-4">
                    <p class="text-gray-700 dark:text-gray-300 mb-4">${message}</p>
                    <div class="flex justify-end">
                        <button class="px-4 py-2 bg-primary text-white hover:bg-primary-dark rounded" onclick="this.closest('.fixed').remove()">OK</button>
                    </div>
                </div>
            `;
            document.body.appendChild(modal);
        }
    </script>
</body>
</html>
