# Qlik Nprinting RabbitMQ Log Checker
- The app to read Qlik Nprinting RabbitMQ Log
- It may assist you to analysis Qlik Nprintnig RabbitMQ related incidents

# Requirement
- The app works on QlikView Desktop
- License verseion of QlikView Desktop is necessary to use this app.
- More logs volumn, more machine resource consumed. If resource shortage occurs, please either reduce the logs volumn or increase machine resource. 

# Instruction
1. Download "NP_RabbitMQLog-Checker-v1.0.qvw" onto your Windows Machine where installed QlikView Desktop.
2. Collect Qlik Nprinting RabbitMQ logs from Nprinting Engine machine and copy them into a folder where is reachable from Qlikiew Desktop
   Note: RabbitMQ Log file name is typically rabbit@[MachineName].log (only one file)
3. Open "NP_RabbitMQLog-Checker-v1.0.qvw" using QlikView Desktop.
4. At "Qlik Nprinting RabbitMQ Log Path" section on Configuration Sheet, Enter file path where you stored RabbitMQ log in No2.
  By default the file path is set to "C:\yheTemp\Nprinting\RabbitMQ\Log\rabbit@QlikServer1.log", please change it to fit to your environment
5. Click Reload button on Configuration Sheet. Logs will be loaded into the app
6. Go to "Logs" Tab and see the data

# Disclaimer
The application is not supported by Qlik. Please use it on your own risk. 

# License
This project is provided "AS IS", without any warranty, under the MIT License - see the LICENSE file for details
