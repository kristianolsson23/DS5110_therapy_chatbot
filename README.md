# DS5110_Therapy_Chatbot

**Abstract**

With the release and popularity of large language models
such as ChatGPT and Gemini, assistant-style chatbots are
readily available to online users everywhere. Although these
models are trained to be helpful, respectful, and safe for users,
they are not specifically trained to act as a therapist that can
deal with issues such as depression, anxiety, or other mental
health disorders. Mental health issues have become increas-
ingly prevalent, yet access to therapy and counseling remains
limited for many reasons such as costs, stigma, and service
availability. To address this gap, we propose the development
of an AI-powered therapy chatbot using advanced natural
language processing techniques and leveraging the Therapy
Sessions Dataset available on Hugging Face. This chatbot
aims to provide immediate, confidential, and empathetic sup-
port for individuals seeking mental health assistance, serving
as a first step towards professional help or as a supplementary
tool for ongoing therapy.
The secondary goal of the project is to implement a Ray
cluster of workers to allocate the training workload among
multiple workers. We wish to see how this implementation
will improve the therapy chatbot with respect to training ef-
ficiency. We aim to use multiple EC2 GPU instances, where
one will act as the host node and the others will act as the
worker nodes.
The development of TherapyBot is expanded below.
