package main

import "fmt"

func main() {
	var myInt = 1
	var myInt8 int8 = 1
	var myInt16 int16 = 1
	var myInt32 int32 = 1
	var myInt64 int64 = 1
	var myByte byte = 1

	var myUInt uint = 1
	var myUInt8 uint8 = 1
	var myUInt16 uint16 = 1
	var myUInt32 uint32 = 1
	var myUInt64 uint64 = 1
	var myRune rune = 1

	fmt.Println(myInt, myInt8, myInt16, myInt32, myInt64, myByte)
	fmt.Println(myUInt, myUInt8, myUInt16, myUInt32, myUInt64, myRune)
}
