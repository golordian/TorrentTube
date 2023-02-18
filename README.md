# TorrentTube
Youtube Style fourm for publishing videos using webtorrent. 4chan style posting (not user registration required to post content. 

Description - A openly available platform that allows users to access a feed of recently uploaded videos. Videos will play using the WebTorrent Protocol (browser will act as a Torrent Client while watching the video help more users access the video).

Users can upload .mp4 videos without creating an account (self-hosted using WebTorrent Desktop), their IP address will be converted into a random ID which will be used as the Publisher ID.

Uploading Videos - Users will need to fist download and install WebTorrent Desktop and add videos they want to publish here. Once their video is available on the user's WebTorrent Client they copy the magnet link > paste in the ‘publish to TorrentTube'.

Video pages - Each video will have it’s own page/feed (comments and video replies) which will also operate on WebTorrent (like feature starts seeding comment/reply video torrent).

The video’s will appear in the main feed and play when clicked. When user clicks ‘reply', or 'comment’ it will redirect them to the video page to add their reply video (using magnet link to publish self-hosted .mp4). 

Comments - Visitors can post comments or reply videos, all will appear with the same publisher ID (using IP address randomized). Similar to 4chan.org (ReCAPTCHA as bot protection).

Required components - WebTorrent, BrowserFy, Node.js, 
