# Dryad Script

1. Sign up for a Dryad API account by following this [Dryad API Accounts Instruction](https://github.com/datadryad/dryad-app/blob/main/documentation/apis/api_accounts.md)

2. Import the necessary Python modules

```
pip install requests dotenv
```

3. Create a `.env` file in the same directory with the Python script following this:

```
CLIENT_ID={YOUR_DRYAD_CLIENT_ID}
CLIENT_SECRET={YOUR_DRYAD_CLIENT_SECRET}
PARENT_DIRECTORY={YOUR_LOCAL_DIRECTORY_TO_STORE_DOWLOAD_FILE_INCLUDING_SLASH}
```

4. Create a directory `./c:/temp/dryad` to store the download files

5. To get a or multiple dataset(s) with specific `doi:10561/dryad.XXXXXX`, run the script:

`python3 Dryad.py XXXXX1 XXXXXX2 `