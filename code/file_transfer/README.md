# Compile

    make

# Run

- Server

        ./server FILE_TO_SEND

- Client

        ./client HOSTNAME FILENAME_TO_SAVE_AS

# Size of transmit queue / Send buffer

While transferring a file, run:

    ./buff.sh


# Questions / Observations

- What is the difference between transmit queue and send buffer?  
  _sndbuf_ is the maximum size of the sendbuffer, while _txqueue_ is the
  current size.
- The transmit queue size is always 0 (?).
- The send buffer size is constant for entire transfer.
