Download GSE from NCBI
================
Lian Chee Foong
2024-12-25

## A safe and quick method to download expression data from NCBI

# **Using FileZilla to Download GSE Files from NCBI FTP**

## **1. Install FileZilla**

- Download and install FileZilla.

## **2. Connect to the NCBI FTP Server**

1.  Open FileZilla.

2.  Enter the following details in the **Quickconnect** bar:

    - **Host**: `ftp.ncbi.nlm.nih.gov`
    - **Username**: `anonymous` (optional)
    - **Password**: Your email address (optional).
    - **Port**: Leave blank or use `21`.

3.  Click **Quickconnect**.

## **3. Navigate to the GSE Files**

1.  Once connected, locate the GEO series folder in the **Remote Site**
    panel: /geo/series/

2.  Drill down to your desired GSE series folder. For example, for
    GSE12345 /geo/series/GSE123nnn/GSE12345/

## **4. Download Files**

- Select the required files.
- Raw data or expression data files, e.g. .h5 or matrix.mtx.gz, are in
  ‘suppl’ folder.
- In Filezilla, drag and drop files from the **Remote Site** (right) to
  the local folder in the **Local Site** (left).

## **5. Verify the Downloads**

- Check the file sizes to ensure all files are downloaded correctly and
  match the expected file sizes.

## **6. Disconnect**

- Click the **Disconnect** button in FileZilla to close the connection.
