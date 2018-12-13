# 질문을 올려주세요!!!

## 메모리 번지수에 대해 이해가 잘 가지 않습니다

	addi	$sp, $zero, 8
	lw	$t0, -8($sp)
	lw	$t1, -8($sp)
	sub	$t2, $t0, $t1
	beq	$t2, $zero, LLL
	add	$t2, $s0, $s1
	sub	$t3, $s0, $s1
LLL:	add	$t1, $t2, 8
	sub	$t3, $t2, $t1
	sw	$t1, -4($sp)
	sw	$t3, -8($sp)
문제 5:5점) 위 프로그램이 끝난 후 “메모리 4번지”에 저장되어 있는 값은 무엇인가 ? 
이거에서 답이 $t1으로 8이라고 하는데 
