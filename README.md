# 𝗜𝗺𝗽𝗼𝗿𝘁𝗮𝗻𝘁 𝗝𝗲𝘁𝗽𝗮𝗰𝗸 𝗖𝗼𝗺𝗽𝗼𝘀𝗲 𝗧𝗶𝗽𝘀 𝘄𝗵𝗶𝗰𝗵 𝘄𝗶𝗹𝗹 𝗺𝗮𝗸𝗲 𝗱𝗲𝘃𝗲𝗹𝗼𝗽𝗺𝗲𝗻𝘁 𝟮𝗫 𝗲𝗮𝘀𝗶𝗲𝗿 𝗳𝗼𝗿 𝘆𝗼𝘂:

## ʀᴇᴄᴇɴᴛʟʏ ɪ ʜᴀᴠᴇ ꜱᴛᴀʀᴛᴇᴅ ᴜꜱɪɴɢ ᴛʜᴇ ᴍɪɢʜᴛʏ ᴊᴇᴛᴘᴀᴄᴋ ᴄᴏᴍᴘᴏꜱᴇ, ᴏʜ ᴍʏ ɢᴏᴅ ɪᴛ ɪꜱ ꜱᴏ ʜᴀʀᴅ ᴛᴏ ᴡᴏʀᴋ ᴡɪᴛʜ, ᴇᴠᴇɴ ʟɪᴛᴛʟᴇ ᴛʜɪɴɢꜱ ᴍᴀᴋᴇ ᴍᴇ ᴄʀᴀᴢʏ. ꜱᴏ, ɪ ᴛʜᴏᴜɢʜᴛ ʟᴇᴛ'ꜱ ʜᴇʟᴘ ʏᴏᴜ ɢᴜʏꜱ ʙʏ ᴛᴇʟʟɪɴɢ ʏᴏᴜ ᴡʜᴀᴛ ɴᴏᴛ ᴛᴏ ᴅᴏ ɪɴ ᴊᴇᴛᴘᴀᴄᴋ ᴄᴏᴍᴘᴏꜱᴇ ᴀɴᴅ ᴡʜᴀᴛ ʏᴏᴜ ꜱʜᴏᴜʟᴅ ᴅᴏ.

✅ Whenever using repetitive Button, TextView, or any component, create your custom one with keeping the ability to change the attribute with the parameters.

✅ If you need a flag please keep it outside of your composable function else it will reset again and again when it recomposes and your flag will be restored to the initial value

✅ Never use experimental API in release applications because in the next release you might not find them and have to rewrite the whole thing with a new API

✅ Try to use the latest API, item, and component provided by jetpack compose, because you really will need their new apis in order to futureproof your project. Trust me you won't get them in the outdated component or item.

✅ Do not change the package name after the application completion, because you will get some resource-related problems that you won't be able to solve unless you revert back to previous sub-package names.

✅ Always use Hilt not Dagger because it won't support fully by jetpack compose, also always use jetpack compose ViewModel others just won't work or will give you lot's of trouble.

✅ For jetpack compose best architecture is not MVVM but MVI Clean Architecture.

✅ Make your composable functions stateless for testing or using them in lambda functions that don't support composable like onClick{}. By doing this and controlling the state from the parent function, the class you will be able to make your codebase testable, decoupled, and easy to work with.

## Thank you very much, make sure you also share these tips with your fellow android developer.
