# asterisk manager utility scripts

## General

`watched_channels` is a space separated list.

The manager user does not need any write rights, and may only need `read=call` or even `read=` rights.

## notify_incoming_call

Notify pushover.net client on call ringing.

## pbxmute

Mutes ALSA channel on call pickup (and unmutes on hang up).
