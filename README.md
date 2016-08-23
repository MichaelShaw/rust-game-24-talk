# trust-free-talk

# using fswatch + jade to watch and build the talk
fswatch -0 talk.jade | xargs -0 -n 1 -I {} jade --pretty {}