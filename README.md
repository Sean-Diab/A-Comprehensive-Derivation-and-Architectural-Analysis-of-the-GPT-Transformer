This paper presents a complete, technical analysis of the decoder-only, autoregressive transformer
architecture used in state-of-the-art chatbot models. Our goal is to cover most implementation
and mathematical details while maintaining readability. We begin with a detailed
overview of the forward pass, followed by technical operation steps, and conclude with the
derivation of all backpropagation equations. While many resources provide an overview of
GPT architecture, a comprehensive, technical source is virtually nonexistent. This paper aims
to fill that gap by serving as a standalone reference for students, researchers, and practitioners
seeking a full understanding of how state-of-the-art language models like GPT operate
and learn. In particular, it is targeted towards researchers aiming to improve upon current
implementations, as advancements are best made from a solid foundation.
