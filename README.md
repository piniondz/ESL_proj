model.pt - model trained for 200 epochs, size 16,3MB  
model_q.pt - model trained for 200 epochs, quantized, size 12,8MB  
model_a.pt - model trained with quantize aware training for 200 epochs, size 12,8MB  
  
profiler_output_static.html - profiler for model.pt  
profiler_output_static_q.html - profiler for model_q.pt  
profiler_output_aware.html - profiler for model_a.pt  
  
Training model with quantization aware training was much faster and the model is both smaller and has higher accuracy then counterparts
