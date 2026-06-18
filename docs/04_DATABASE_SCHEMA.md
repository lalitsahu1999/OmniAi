# Database Schema

## Users

users

userId

name

email

photo

createdAt

updatedAt

---

## Projects

projects

projectId

ownerId

name

description

status

createdAt

updatedAt

---

## Chats

chats

chatId

projectId

userId

title

createdAt

---

## Messages

messages

messageId

chatId

role

content

model

timestamp

---

## Memories

memories

memoryId

userId

category

content

importance

createdAt

---

## Knowledge Base

knowledge

documentId

projectId

title

fileUrl

embeddingStatus

---

## Files

files

fileId

projectId

type

size

url

---

## Settings

settings

userId

theme

voiceEnabled

selectedModel

language
