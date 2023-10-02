# Clean folder

The script can be called anywhere on the system from the console with the `clean-folder` command.

The script goes through the folder specified during the call and sorts all files into groups:

1. image('JPEG', 'PNG', 'JPG', 'SVG');
2. video files ('AVI', 'MP4', 'MOV', 'MKV');
3. documents ('DOC', 'DOCX', 'TXT', 'PDF', 'XLSX', 'PPTX');
4. music ('MP3', 'OGG', 'WAV', 'AMR');
5. archives ('ZIP', 'GZ', 'TAR');
6. unknown extensions.

## Usage 

The package is installed on the system with the `pip install -e command`. (or `python setup.py install`, requires admin rights).

After installation, the clean_folder package appears in the system.

When the package is installed on the system, the script can be called anywhere from the console with the `clean-folder` command.
