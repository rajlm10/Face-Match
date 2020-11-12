# Face-Match

Face-Match is a real time face detection service which identifies faces provided it has seen them before based purely on image-processing.


## Results

Here is what face-match can do -

This is a result which shows how face-match has detected my name after finding similarities from my [picture](./known_people/Raj.jpg) in the **known_people** directory

![Live detection](./docs/images/result.jpg) 



## Installations and Setup




Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the dependencies.




```bash
pip3 install -r requirements.txt
```
## Structure of the project
- The **known_people** directory contains **.jpg** images of people Face-Match can detect.
- The **recognise.py** file contains the main image-processing code in python3. 
- The **docs/images** directory contains images used in the README file.

## Usage
Please add  ```name.jpg```  images to the known_people directory where **name** is the result you would like face-match to display during real-time detection

```python
python3 recognise.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
