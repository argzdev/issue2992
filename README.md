# issue2992
### Prerequisite
- Add google-services.json
### Summary
- The issue is that addOnSuccessListener is annotated as @NonNull, and yet it still receives and returns null on it's success callback.
- Running the app will immediately log "issue2992: is null"
