FROM python:3.8

WORKDIR /app

RUN pip install numpy pandas scikit-learn jupyter matplotlib

EXPOSE 8888

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]
