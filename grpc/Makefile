generate:
	make generate-note-api

generate-note-api:
	mkdir  "pkg/note_v1"

	protoc api/note_v1/note.proto \
 	--go_out=pkg/note_v1 \
 	--go_opt=paths=source_relative \
 	--go-grpc_out=pkg/note_v1 \
 	--go-grpc_opt=paths=source_relative