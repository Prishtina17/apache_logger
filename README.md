Apache logger
Установка: pip install requirements.txt
субд:
  postgres
веб приложение: 
  python api.py
  get 127.0.0.1/logs?ip&start_date&end_date
консольное приложение:
  python main.py
  команда export читает логи из файлов, которые предварительно должны быть указаны в config.py
  команда select filter1 filter2 ... читает логи из дб
