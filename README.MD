Introduction

A recipe CRUD api.

Main Features:
    Users can add images to the api
    The name of the image is made random
    Nested serializer for Ingredients


Recipe: 
    name
    cooking instructions
    preparation time
    cooking time
    image 

Ingredients:
    name
    amount
    measurement
    

Usage: 

    python3 -m venv venv

    pip install -r requirements.txt

    Input following:
                    Recipe: 
                        name
                            Ingredients:
                                name
                                amount
                                measurement
                        cooking instructions
                        preparation time
                        cooking time
                        image 