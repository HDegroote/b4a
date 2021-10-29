# Buffer for Array

Buffer for Array (B4A) provides a set of functions for bridging the gap between the Node.js `Buffer` class and the `Uint8Array` class. A browser compatibility layer is also included, making it possible to use B4A in both Node.js and browsers without having to worry about whether you're dealing with buffers or typed arrays.

## Installation

```sh
npm install b4a
```

## API

#### `b4a.isBuffer(value)`

See https://nodejs.org/api/buffer.html#static-method-bufferisbufferobj

This will also return `true` when passed a `Uint8Array`.

#### `b4a.alloc(size)`

See https://nodejs.org/api/buffer.html#static-method-bufferallocsize-fill-encoding

#### `b4a.allocUnsafe(size)`

See https://nodejs.org/api/buffer.html#static-method-bufferallocunsafesize

#### `b4a.allocUnsafeSlow(size)`

See https://nodejs.org/api/buffer.html#static-method-bufferallocunsafeslowsize

#### `b4a.byteLength(string)`

See https://nodejs.org/api/buffer.html#static-method-bufferbytelengthstring-encoding

#### `b4a.compare(buf1, buf2)`

See https://nodejs.org/api/buffer.html#static-method-buffercomparebuf1-buf2

#### `b4a.concat(buffers[, totalLength])`

See https://nodejs.org/api/buffer.html#static-method-bufferconcatlist-totallength

#### `b4a.copy(source, target[, targetStart[, sourceStart[, sourceEnd]]])`

See https://nodejs.org/api/buffer.html#bufcopytarget-targetstart-sourcestart-sourceend

#### `b4a.equals(buf1, buf2)`

See https://nodejs.org/api/buffer.html#bufequalsotherbuffer

#### `b4a.from(array)`

See https://nodejs.org/api/buffer.html#static-method-bufferfromarray

#### `b4a.from(arrayBuffer[, byteOffset[, length]])`

See https://nodejs.org/api/buffer.html#static-method-bufferfromarraybuffer-byteoffset-length

#### `b4a.from(buffer)`

See https://nodejs.org/api/buffer.html#static-method-bufferfrombuffer

#### `b4a.from(string[, encoding])`

See https://nodejs.org/api/buffer.html#static-method-bufferfromstring-encoding

#### `b4a.toBuffer(buffer)`

Convert a buffer to its canonical representation. In Node.js, the canonical representation is a `Buffer`. In the browser, the canonical reprensetation is a `Uint8Array`.

#### `b4a.toString([encoding[, start[, end]]])`

See https://nodejs.org/api/buffer.html#buftostringencoding-start-end

#### `b4a.write(string[, offset[, length]][, encoding])`

See https://nodejs.org/api/buffer.html#bufwritestring-offset-length-encoding
