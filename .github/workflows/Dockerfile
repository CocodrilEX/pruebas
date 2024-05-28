name: Build and push
  uses: docker/build-push-action@v5
  with:
    context: .  # Assuming Dockerfile is in the root directory
    file: ./src/Dockerfile  # Use the relative path if in a subdirectory
    push: true
    tags: ${{ secrets.DOCKERHUB_USERNAME }}/clockbox:latest
