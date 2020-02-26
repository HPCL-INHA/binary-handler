# binary-handler

Binary to LLVM IR Project List

https://github.com/decomp/decomp/blob/master/front-end.md

대부분은 Recompile을 지원하지 않음

## retdec

No recompile support

LLVM IR 변환 후 컴파일 불가능

구조체, 스택, 배열 선언 오류 있음

## llvm-mctoll

재컴파일 지원. 단, extra/dynamic symbol들을 모두 restrict해야함

## remill, mcsema

Dyninst 컴파일 문제있음

IDA Pro 7.1 이상 필요함

## 
