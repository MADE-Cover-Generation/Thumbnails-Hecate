FROM valian/docker-python-opencv-ffmpeg


#install hecate
RUN python -m pip install --no-deps -U yt-dlp
RUN cd /home && git clone https://github.com/yahoo/hecate.git
RUN cd /home/hecate && make all 
RUN cd /home/hecate && make distribute
	

