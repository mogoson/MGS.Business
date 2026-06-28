[TOC]

# Framework

## Summary

Framework template for Unity app.

## IO

### MGS.IOUtility

- DirectoryUtility, Create/Delete directory.
- FileUtility, Read/Write file.

### MGS.StreamingIO

- StreamingIO, Read asset from Unity streamingAssetsPath.
- PersistentIO, Read/Write asset from/to Unity persistentDataPath.

### MGS.StreamingPorter

- StreamingPorter, Transport manifest assets from streaming to persistent path.

### MGS.JsonAvatar

- JsonConvert, Convert json.
- FieldOnlyContractResolver, Contract resolver for field only.
- JsonAvatar, Avatar to pull data from file and push data to file.

## Message

### MGS.MessageBus

- MessageBus, Subscribe/Unsubscribe/Spread/Clear message.

## Collection

###  MGS.MonoCollection

- MonoCollection, Manage items for data list.
- PageCollection, Manage items for page data.

## Coroutine

### MGS.MonoAgent

- MonoAgent, Provide an instance of MonoBehaviour in normal C# Class.
- CoroutineAgent, Provide generic routine and start coroutine.
- RoutineAgent, Provide generic routine.

------

Copyright © 2026 Mogoson.	mogoson@outlook.com