# always put this at the top of a dockerfile. This tells docker to use that image as a base image for this container.
FROM alpine

# Step 2: Download and install dependency. RUN is used to execute any arbitrary command within the container.
RUN apk add --update redis
RUN apk add --update gcc

# Step 3: Tell the image what to do when it starts as container
CMD ["redis-server"]