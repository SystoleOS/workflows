# Use the gentoo/stage3 image as the base
FROM gentoo/stage3

# Any additional steps to transform gentoo/stage3 into systoleos/stage3 go here.
# For example, you might want to update the package database and upgrade packages:
RUN emerge-webrsync  && emerge -avuDN @world

# Continue with any other commands you need to create your systoleos/stage3 image...
