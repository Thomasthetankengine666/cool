Skyrim SSE v1.6.640
CrashLoggerSSE v1-8-0-0 Feb  1 2023 00:20:05

Unhandled exception "EXCEPTION_ACCESS_VIOLATION" at 0x7FF6CBB215B6 SkyrimSE.exe+0C615B6	mov r8, [rdx]

SYSTEM SPECS:
	OS: Microsoft Windows 10 Home v10.0.19041
	CPU: GenuineIntel Intel(R) Core(TM) i5-9300H CPU @ 2.40GHz
	GPU #1: Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]
	GPU #2: Intel CoffeeLake-H GT2 [UHD Graphics 630]
	GPU #3: Microsoft Basic Render Driver
	PHYSICAL MEMORY: 14.76 GB/15.85 GB

PROBABLE CALL STACK:
	[ 0] 0x7FF6CBB215B6 SkyrimSE.exe+0C615B6 -> 69166+0x6   BSFixedString::Copy
	[ 1] 0x7FF6CBB54A3C SkyrimSE.exe+0C94A3C -> 70352+0x9C  BSStream::sub
	[ 2] 0x7FF6CBB5A6F1 SkyrimSE.exe+0C9A6F1 -> 70501+0x21  NiObjectNET::LoadBinary
	[ 3] 0x7FF6CBB50610 SkyrimSE.exe+0C90610 -> 70245+0x20  NiAVObject::LoadBinary
	[ 4] 0x7FF6CBB6C12A SkyrimSE.exe+0CAC12A -> 70913+0x1A  BSGeometry::LoadBinary
	[ 5] 0x7FF6CBB61C56 SkyrimSE.exe+0CA1C56 -> 70650+0x16  BSTriShape::LoadBinary
	[ 6] 0x7FF6CBB56365 SkyrimSE.exe+0C96365 -> 70381+0x1C5 NiStream::Func15
	[ 7] 0x7FF6CBB5433D SkyrimSE.exe+0C9433D -> 70333+0x2D  NiStream::Func1
	[ 8] 0x7FF6CBC40B88 SkyrimSE.exe+0D80B88 -> 75949+0x88
	[ 9] 0x7FF6CBC37DC9 SkyrimSE.exe+0D77DC9 -> 75773+0xC9
	[10] 0x7FF6CB0872E0 SkyrimSE.exe+01C72E0 -> 15434+0x110
	[11] 0x7FF6CB087487 SkyrimSE.exe+01C7487 -> 15435+0x137
	[12] 0x7FF6CBC39960 SkyrimSE.exe+0D79960 -> 75795+0x150
	[13] 0x7FF6CBC3A5B0 SkyrimSE.exe+0D7A5B0 -> 75814+0x30
	[14] 0x7FF6CBB3DA0F SkyrimSE.exe+0C7DA0F -> 69809+0x4F  BSResource__EntryDB_gs_T1_ge_::sub
	[15] 0x7FF6CBC3681D SkyrimSE.exe+0D7681D -> 75716+0x5D  IOManager::Func21
	[16] 0x7FF6CBC3312F SkyrimSE.exe+0D7312F -> 75651+0x13F
	[17] 0x7FF6CBB05E4D SkyrimSE.exe+0C45E4D -> 68445+0x3D  StartAddress_0
	[18] 0x7FFE438A7604 KERNEL32.DLL+0017604
	[19] 0x7FFE457E26A1    ntdll.dll+00526A1

REGISTERS:
	RAX 0x25BEF2C0A08      (void*)
	RCX 0x25C152D5A90      (void*)
	RDX 0x25DF2732BA8      (size_t) [2602522848168]
	RBX 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	RSP 0xDE43D0EA80       (void*)
	RBP 0xDE43D0EC90       (void*)
	RSI 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	RDI 0x25C152D5A90      (void*)
	R8  0x4                (size_t) [4]
	R9  0x7FFE2E1E140A     (void* -> VCRUNTIME140.dll+000140A	mov ecx, [rdx])
	R10 0x7FFE2E1E0000     (void*)
	R11 0xDE43D0EA60       (void*)
	R12 0x0                (size_t) [0]
	R13 0x7FF6CDF6E7B0     (void* -> SkyrimSE.exe+30AE7B0	fdiv st0, dword ptr [rbx+0x7FF6CC71])
	R14 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	R15 0xFA               (size_t) [250]

STACK:
	[RSP+0   ] 0x25C152D5A90      (void*)
	[RSP+8   ] 0x6C               (size_t) [108]
	[RSP+10  ] 0x2                (size_t) [2]
	[RSP+18  ] 0x0                (size_t) [0]
	[RSP+20  ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+28  ] 0x7FF6CBB54A3C     (void* -> SkyrimSE.exe+0C94A3C	mov rbx, [rsp+0x58])
	[RSP+30  ] 0x4                (size_t) [4]
	[RSP+38  ] 0xDE43D0EBB0       (void*)
	[RSP+40  ] 0x259230984F0      (BSResource::`anonymous namespace'::LooseFileStream*)
	[RSP+48  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+50  ] 0xDE00000001       (size_t) [953482739713]
	[RSP+58  ] 0x7FF6CBB460AF     (void* -> SkyrimSE.exe+0C860AF	mov ebx, eax)
	[RSP+60  ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+68  ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+70  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+78  ] 0x7FF6CBB5A6F1     (void* -> SkyrimSE.exe+0C9A6F1	mov rcx, rdi)
	[RSP+80  ] 0xDE00000004       (size_t) [953482739716]
	[RSP+88  ] 0x25C152D5A80      (BSTriShape*)
		RTTIName: "BSTriShape"
		Flags: kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController
	[RSP+90  ] 0xFFFFFFFF4068E434 (size_t) [uint: 18446744070495200308 int: -3214351308]
	[RSP+98  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+A0  ] 0x25C152D5A80      (BSTriShape*)
		RTTIName: "BSTriShape"
		Flags: kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController
	[RSP+A8  ] 0x7FF6CBB50610     (void* -> SkyrimSE.exe+0C90610	mov rbx, [rsi+0x298])
	[RSP+B0  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+B8  ] 0xFA               (size_t) [250]
	[RSP+C0  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+C8  ] 0x7FF6CDF6E7B0     (void* -> SkyrimSE.exe+30AE7B0	fdiv st0, dword ptr [rbx+0x7FF6CC71])
	[RSP+D0  ] 0x0                (size_t) [0]
	[RSP+D8  ] 0x2BC              (size_t) [700]
	[RSP+E0  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+E8  ] 0x7FF6CBB6C12A     (void* -> SkyrimSE.exe+0CAC12A	lea rbx, [rdi+0x110])
	[RSP+F0  ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+F8  ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+100 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+108 ] 0x25C152D5A80      (BSTriShape*)
		RTTIName: "BSTriShape"
		Flags: kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController
	[RSP+110 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+118 ] 0x25C152D5C00      (BSTriShape*)
		Name: "C_ChunkBaseHelper02:0"
		RTTIName: "BSTriShape"
		Flags: kHidden | kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController | kNoAnimSyncS
		Name: "C_ChunkBaseHelper02:0"
	[RSP+120 ] 0x25C152D5A80      (BSTriShape*)
		RTTIName: "BSTriShape"
		Flags: kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController
	[RSP+128 ] 0x7FF6CBB61C56     (void* -> SkyrimSE.exe+0CA1C56	mov rbx, [rsi+0x298])
	[RSP+130 ] 0x2B8              (size_t) [696]
	[RSP+138 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+140 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+148 ] 0xDE0000000D       (size_t) [953482739725]
	[RSP+150 ] 0xDE00000001       (size_t) [953482739713]
	[RSP+158 ] 0x7FF6CBB51595     (void* -> SkyrimSE.exe+0C91595	)
	[RSP+160 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+168 ] 0x7FF6CC4DA2B8     (void* -> SkyrimSE.exe+161A2B8	mov eax, 0xF6CC335F)
	[RSP+170 ] 0x25C152D5A80      (BSTriShape*)
		RTTIName: "BSTriShape"
		Flags: kSelectiveUpdate | kSelectiveUpdateTransforms | kSelectiveUpdateController
	[RSP+178 ] 0xDE43D0EC90       (void*)
	[RSP+180 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+188 ] 0x7FF6CBB56365     (void* -> SkyrimSE.exe+0C96365	mov rax, [rsi])
	[RSP+190 ] 0xDE0000024C       (size_t) [953482740300]
	[RSP+198 ] 0xDE0000015C       (size_t) [953482740060]
	[RSP+1A0 ] 0xDE00000002       (size_t) [953482739714]
	[RSP+1A8 ] 0x25A9738B1C0      (NiPSysBoundUpdateModifier*)
	[RSP+1B0 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+1B8 ] 0x7FF6CC4DA2B8     (void* -> SkyrimSE.exe+161A2B8	mov eax, 0xF6CC335F)
	[RSP+1C0 ] 0xDE43D0EC48       (void*)
	[RSP+1C8 ] 0x25A4C4873D0      (ScrapHeap*)
	[RSP+1D0 ] 0x25BEF261000      (void*)
	[RSP+1D8 ] 0xDE00000100       (size_t) [953482739968]
	[RSP+1E0 ] 0xDE00000090       (size_t) [953482739856]
	[RSP+1E8 ] 0x25A4C4873D0      (ScrapHeap*)
	[RSP+1F0 ] 0x25C152D2080      (void*)
	[RSP+1F8 ] 0x200              (size_t) [512]
	[RSP+200 ] 0xDE000001A0       (size_t) [953482740128]
	[RSP+208 ] 0x25A4C487468      (void*)
	[RSP+210 ] 0x7FF6CDF70480     (void* -> SkyrimSE.exe+30B0480	add [rax], al)
	[RSP+218 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+220 ] 0x7FF6CDF73390     (void* -> SkyrimSE.exe+30B3390	add [rax], eax)
	[RSP+228 ] 0x25BDDA34B18      (void*)
	[RSP+230 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+238 ] 0x7FF6CBB5433D     (void* -> SkyrimSE.exe+0C9433D	jmp 0x00007FF6CBB54341)
	[RSP+240 ] 0xDE43D0EE10       (BSStream*)
		Header: author: Liz.rapp version: 100 processScript:  exportScript:  PE Anim
		inputFilePath: "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+248 ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+250 ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+258 ] 0x0                (size_t) [0]
	[RSP+260 ] 0xDE43D0EF18       (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+268 ] 0x7FF6CBC40B88     (void* -> SkyrimSE.exe+0D80B88	movzx edi, al)
	[RSP+270 ] 0x0                (size_t) [0]
	[RSP+278 ] 0x128              (size_t) [296]
	[RSP+280 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+288 ] 0x8                (size_t) [8]
	[RSP+290 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+298 ] 0x7FF6CC4F8408     (void* -> SkyrimSE.exe+1638408	mov al, 0x6B)
	[RSP+2A0 ] 0x0                (size_t) [0]
	[RSP+2A8 ] 0x25A4C487468      (void*)
	[RSP+2B0 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+2B8 ] 0x7FF6CBC37DC9     (void* -> SkyrimSE.exe+0D77DC9	movzx ebx, al)
	[RSP+2C0 ] 0x25A4C486D00      (void*)
	[RSP+2C8 ] 0xDE43D0EE40       (void*)
	[RSP+2D0 ] 0x0                (size_t) [0]
	[RSP+2D8 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+2E0 ] 0x25BDDA34AD0      (void*)
	[RSP+2E8 ] 0x25B94FC91A0      (void*)
	[RSP+2F0 ] 0x25A00000002      (void*)
	[RSP+2F8 ] 0x7FFE3F140000     (void* -> d3d11.dll+0010000	add [rax], al)
	[RSP+300 ] 0x25A4C487468      (void*)
	[RSP+308 ] 0xDE43D0EE28       (void*)
	[RSP+310 ] 0x25A4C4876E0      (void*)
	[RSP+318 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+320 ] 0x25A198D68C0      (void*)
	[RSP+328 ] 0x7FFE3F14E5FF     (void* -> d3d11.dll+001E5FF	mov [rdi+0x08], esi)
	[RSP+330 ] 0x25B94FC8C20      (void*)
	[RSP+338 ] 0xDE43D0EE58       (void*)
	[RSP+340 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+348 ] 0x18021B130        (void* -> d3d11.dll+021B130	sbb dl, dh)
	[RSP+350 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+358 ] 0x7FF6CC71A910     (void* -> SkyrimSE.exe+185A910	)
	[RSP+360 ] 0x25A0003FEC0      (void*)
	[RSP+368 ] 0x7FF6CBB718D0     (void* -> SkyrimSE.exe+0CB18D0	push rbx)
	[RSP+370 ] 0x7FF6CBB71940     (void* -> SkyrimSE.exe+0CB1940	push rbx)
	[RSP+378 ] 0x259230984F0      (BSResource::`anonymous namespace'::LooseFileStream*)
	[RSP+380 ] 0x0                (size_t) [0]
	[RSP+388 ] 0x3FEC0            (size_t) [261824]
	[RSP+390 ] 0x7FF6CC4E7CB8     (void* -> SkyrimSE.exe+1627CB8	cmp byte ptr [rdi+0x01], 0xCB)
	[RSP+398 ] 0x2E7A694C00000064 (size_t) [3349105048041816164]
	[RSP+3A0 ] 0x656C0070706172   (size_t) [28547721789989234]
	[RSP+3A8 ] 0x25B94FC8C20      (void*)
	[RSP+3B0 ] 0x0                (size_t) [0]
	[RSP+3B8 ] 0x0                (size_t) [0]
	[RSP+3C0 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+3C8 ] 0x25B94FC8C20      (void*)
	[RSP+3D0 ] 0x25AFF766501      (void*)
	[RSP+3D8 ] 0x69747000A6B1D912 (size_t) [7598821619379853586]
	[RSP+3E0 ] 0x69772064657A696D (size_t) [7599578511782340973]
	[RSP+3E8 ] 0x4E20455353206874 (size_t) [5629575758392354932]
	[RSP+3F0 ] 0x6D6974704F204649 (size_t) [7883960648401438281]
	[RSP+3F8 ] 0x2E33762072657A69 (size_t) [3329134431287212649]
	[RSP+400 ] 0x2E362E30         (size_t) [775302704]
	[RSP+408 ] 0xDE43D0F050       (void*)
	[RSP+410 ] 0x8                (size_t) [8]
	[RSP+418 ] 0x204550203F21D43B (size_t) [2325352882035086395]
	[RSP+420 ] 0x412063006D696E41 (size_t) [4692859665206832705]
	[RSP+428 ] 0x25B76007472      (void*)
	[RSP+430 ] 0xDE43D0F050       (void*)
	[RSP+438 ] 0x25B94FC8C40      (void*)
	[RSP+440 ] 0x800000001        (size_t) [34359738369]
	[RSP+448 ] 0x25AFF766588      (void*)
	[RSP+450 ] 0x7FFE3F3618D0     (void* -> d3d11.dll+02318D0	adc [rdi+rbx*1+0x7E025953], bl)
	[RSP+458 ] 0x7FFE3F328E90     (void* -> d3d11.dll+01F8E90	add [rax], eax)
	[RSP+460 ] 0x7FFE80000004     (size_t) [140731045904388]
	[RSP+468 ] 0x0                (size_t) [0]
	[RSP+470 ] 0x18021B0F0        (void* -> d3d11.dll+021B0F0	adc bl, cl)
	[RSP+478 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+480 ] 0x25AFF7664F0      (void*)
	[RSP+488 ] 0x1                (size_t) [1]
	[RSP+490 ] 0xC14020007        (size_t) [51875282951]
	[RSP+498 ] 0x53454D5C61746164 (size_t) [6000287137708400996]
	[RSP+4A0 ] 0x676E75645C534548 (size_t) [7453023507250890056]
	[RSP+4A8 ] 0x726F6E5C736E6F65 (size_t) [8245930786091331429]
	[RSP+4B0 ] 0x726365735C636964 (size_t) [8242543289163802980]
	[RSP+4B8 ] 0x615C737361707465 (size_t) [7015609258929583205]
	[RSP+4C0 ] 0x5C646574616D696E (size_t) [6657557699685607790]
	[RSP+4C8 ] 0x726F6F646D736D72 (size_t) [8245931919862361458]
	[RSP+4D0 ] 0x6573726F6E5C3230 (size_t) [7310312443070919216]
	[RSP+4D8 ] 0x6F6F646D736D7263 (size_t) [8029747081875649123]
	[RSP+4E0 ] 0x696E2E32306D7372 (size_t) [7597060414516327282]
	[RSP+4E8 ] 0x666C456B72610066 (size_t) [7380350217136177254]
	[RSP+4F0 ] 0x66696E2E         (size_t) [1718185518]
	[RSP+4F8 ] 0x7FFE3F21E2A3     (void* -> d3d11.dll+00EE2A3	mov eax, ebx)
	[RSP+500 ] 0x18021B0F0        (void* -> d3d11.dll+021B0F0	adc bl, cl)
	[RSP+508 ] 0x25AFF766580      (void*)
	[RSP+510 ] 0xDE43D0F050       (void*)
	[RSP+518 ] 0x259324F0B30      (myID3D11Device*)
	[RSP+520 ] 0xDE00000001       (size_t) [953482739713]
	[RSP+528 ] 0x25AFF766580      (void*)
	[RSP+530 ] 0x25AA29B47D0      (void*)
	[RSP+538 ] 0x18004D220        (void* -> d3d11.dll+004D220	cmp [0x00000001805F89C8], rbp)
	[RSP+540 ] 0x25AFF766580      (void*)
	[RSP+548 ] 0x0                (size_t) [0]
	[RSP+550 ] 0x25B769036F8      (void*)
	[RSP+558 ] 0x259324F0B30      (myID3D11Device*)
	[RSP+560 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+568 ] 0x80000000002      (size_t) [8796093022210]
	[RSP+570 ] 0x800              (size_t) [2048]
	[RSP+578 ] 0x10000004D        (size_t) [4294967373]
	[RSP+580 ] 0xC00000000        (size_t) [51539607552]
	[RSP+588 ] 0x7FFE0D3E3911     (void* -> tbbmalloc.dll+0013911	xor ecx, ecx)
	[RSP+590 ] 0x25B769036F8      (void*)
	[RSP+598 ] 0xFFFF0101FFFFFFFE (size_t) [uint: 18446463706834403326 int: -280366875148290]
	[RSP+5A0 ] 0x0                (size_t) [0]
	[RSP+5A8 ] 0x7FF6CC716CF8     (void* -> SkyrimSE.exe+1856CF8	)
	[RSP+5B0 ] 0x25C152F8108      (void*)
	[RSP+5B8 ] 0xFA000000FA       (size_t) [1073741824250]
	[RSP+5C0 ] 0x400000000FA      (size_t) [4398046511354]
	[RSP+5C8 ] 0x7FF6CC716D18     (void* -> SkyrimSE.exe+1856D18	adc [rcx+0x7FF6CBB5], dl)
	[RSP+5D0 ] 0x25BEF261400      (char*) "`"
	[RSP+5D8 ] 0xFA000000FA       (size_t) [1073741824250]
	[RSP+5E0 ] 0x1000000FA        (size_t) [4294967546]
	[RSP+5E8 ] 0x7FF6CC716CF8     (void* -> SkyrimSE.exe+1856CF8	)
	[RSP+5F0 ] 0x0                (size_t) [0]
	[RSP+5F8 ] 0x0                (size_t) [0]
	[RSP+600 ] 0x100000000        (size_t) [4294967296]
	[RSP+608 ] 0x7FF6CC716D38     (void* -> SkyrimSE.exe+1856D38	adc byte ptr [rax+0x7FF6CBB5], 0x00)
	[RSP+610 ] 0x25BEF2C0A08      (void*)
	[RSP+618 ] 0x5800000058       (size_t) [377957122136]
	[RSP+620 ] 0x8000000058       (size_t) [549755813976]
	[RSP+628 ] 0xDE43D0EDD8       (BSResourceNiBinaryStream*)
	[RSP+630 ] 0x0                (size_t) [0]
	[RSP+638 ] 0x0                (size_t) [0]
	[RSP+640 ] 0x7FF6CC716D88     (void* -> SkyrimSE.exe+1856D88	)
	[RSP+648 ] 0x7FFE00000025     (size_t) [140728898420773]
	[RSP+650 ] 0x25C15386840      (void*)
	[RSP+658 ] 0x25A00000000      (void*)
	[RSP+660 ] 0x0                (size_t) [0]
	[RSP+668 ] 0x0                (size_t) [0]
	[RSP+670 ] 0xF9               (size_t) [249]
	[RSP+678 ] 0x7FFE00000000     (size_t) [140728898420736]
	[RSP+680 ] 0x0                (size_t) [0]
	[RSP+688 ] 0x0                (size_t) [0]
	[RSP+690 ] 0xFFFFFFFF00000002 (size_t) [uint: 18446744069414584322 int: -4294967294]
	[RSP+698 ] 0xFFFFFFFF         (size_t) [4294967295]
	[RSP+6A0 ] 0x0                (size_t) [0]
	[RSP+6A8 ] 0x0                (size_t) [0]
	[RSP+6B0 ] 0x0                (size_t) [0]
	[RSP+6B8 ] 0x0                (size_t) [0]
	[RSP+6C0 ] 0x0                (size_t) [0]
	[RSP+6C8 ] 0x0                (size_t) [0]
	[RSP+6D0 ] 0x0                (size_t) [0]
	[RSP+6D8 ] 0x0                (size_t) [0]
	[RSP+6E0 ] 0x0                (size_t) [0]
	[RSP+6E8 ] 0x0                (size_t) [0]
	[RSP+6F0 ] 0x0                (size_t) [0]
	[RSP+6F8 ] 0x0                (size_t) [0]
	[RSP+700 ] 0x0                (size_t) [0]
	[RSP+708 ] 0x0                (size_t) [0]
	[RSP+710 ] 0x0                (size_t) [0]
	[RSP+718 ] 0x0                (size_t) [0]
	[RSP+720 ] 0x0                (size_t) [0]
	[RSP+728 ] 0x0                (size_t) [0]
	[RSP+730 ] 0x0                (size_t) [0]
	[RSP+738 ] 0x0                (size_t) [0]
	[RSP+740 ] 0x0                (size_t) [0]
	[RSP+748 ] 0x0                (size_t) [0]
	[RSP+750 ] 0x0                (size_t) [0]
	[RSP+758 ] 0x0                (size_t) [0]
	[RSP+760 ] 0x0                (size_t) [0]
	[RSP+768 ] 0x0                (size_t) [0]
	[RSP+770 ] 0x0                (size_t) [0]
	[RSP+778 ] 0x0                (size_t) [0]
	[RSP+780 ] 0x0                (size_t) [0]
	[RSP+788 ] 0x0                (size_t) [0]
	[RSP+790 ] 0x0                (size_t) [0]
	[RSP+798 ] 0x0                (size_t) [0]
	[RSP+7A0 ] 0x0                (size_t) [0]
	[RSP+7A8 ] 0x0                (size_t) [0]
	[RSP+7B0 ] 0x7FF6CCD65B50     (type_info*)
	[RSP+7B8 ] 0x7FF6CBAFE93F     (void* -> SkyrimSE.exe+0C3E93F	cmp [rdi], eax)
	[RSP+7C0 ] 0xDE43D0F688       (`IOManager::DoOnPreRunTask'::`2'::Pauser*)
	[RSP+7C8 ] 0xBD               (size_t) [189]
	[RSP+7D0 ] 0x25BDDA18FE0      (TESObjectREFR*)
		Object Reference: 
		File: "Containers and Leveled Lists Fixes.esp"
		Modified by: Skyrim.esm -> Unlucky Loot.esp -> Containers and Leveled Lists Fixes.esp
		Flags: 0x08400009 kDestructible | kInitialized | kFormRetainsID | kDisableFade
		Name: "Food Barrel"
		FormID: 0x00000845
		FormType: Container (28)
		File: "Skyrim.esm"
		Flags: 0x00000009 kDestructible | kInitialized
		FormID: 0x000DE0E4
		FormType: Reference (61)
	[RSP+7D8 ] 0x7FF6CAFEBD6E     (void* -> SkyrimSE.exe+012BD6E	test rax, rax)
	[RSP+7E0 ] 0xDE43D0F4A8       (void*)
	[RSP+7E8 ] 0x7FF6CBB5AF48     (void* -> SkyrimSE.exe+0C9AF48	nop)
	[RSP+7F0 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+7F8 ] 0x7FF6CB0160EE     (void* -> SkyrimSE.exe+01560EE	mov ebp, eax)
	[RSP+800 ] 0x7FF6CDF786E0     (BSResource::EntryDB<BSTextureDB::DBTraits>*)
	[RSP+808 ] 0x0                (size_t) [0]
	[RSP+810 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+818 ] 0xBD               (size_t) [189]
	[RSP+820 ] 0xDE43D0F4C0       (void*)
	[RSP+828 ] 0x7FF6CBB23069     (void* -> SkyrimSE.exe+0C63069	cmp [rbx], eax)
	[RSP+830 ] 0xDE43D0F4C0       (void*)
	[RSP+838 ] 0xDE43D0F340       (void*)
	[RSP+840 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+848 ] 0x51               (size_t) [81]
	[RSP+850 ] 0x7FF6CDF70480     (void* -> SkyrimSE.exe+30B0480	add [rax], al)
	[RSP+858 ] 0x7FF6CDF73390     (void* -> SkyrimSE.exe+30B3390	add [rax], eax)
	[RSP+860 ] 0xDE43D0F5E0       (void*)
	[RSP+868 ] 0x40000000         (size_t) [1073741824]
	[RSP+870 ] 0xDE43D0F4C0       (void*)
	[RSP+878 ] 0x0                (size_t) [0]
	[RSP+880 ] 0x25BDDA34AF0      (void*)
	[RSP+888 ] 0x7FF6CBB21594     (void* -> SkyrimSE.exe+0C61594	mov rax, rbx)
	[RSP+890 ] 0xDE43D0F348       (void*)
	[RSP+898 ] 0xDE43D0F4C0       (void*)
	[RSP+8A0 ] 0xDE43D0F4C0       (void*)
	[RSP+8A8 ] 0x0                (size_t) [0]
	[RSP+8B0 ] 0x0                (size_t) [0]
	[RSP+8B8 ] 0x0                (size_t) [0]
	[RSP+8C0 ] 0x0                (size_t) [0]
	[RSP+8C8 ] 0x0                (size_t) [0]
	[RSP+8D0 ] 0x0                (size_t) [0]
	[RSP+8D8 ] 0x0                (size_t) [0]
	[RSP+8E0 ] 0x0                (size_t) [0]
	[RSP+8E8 ] 0x0                (size_t) [0]
	[RSP+8F0 ] 0x0                (size_t) [0]
	[RSP+8F8 ] 0x0                (size_t) [0]
	[RSP+900 ] 0x0                (size_t) [0]
	[RSP+908 ] 0x0                (size_t) [0]
	[RSP+910 ] 0x0                (size_t) [0]
	[RSP+918 ] 0x0                (size_t) [0]
	[RSP+920 ] 0x0                (size_t) [0]
	[RSP+928 ] 0x0                (size_t) [0]
	[RSP+930 ] 0x0                (size_t) [0]
	[RSP+938 ] 0x0                (size_t) [0]
	[RSP+940 ] 0x0                (size_t) [0]
	[RSP+948 ] 0x0                (size_t) [0]
	[RSP+950 ] 0x0                (size_t) [0]
	[RSP+958 ] 0x0                (size_t) [0]
	[RSP+960 ] 0x0                (size_t) [0]
	[RSP+968 ] 0x0                (size_t) [0]
	[RSP+970 ] 0x0                (size_t) [0]
	[RSP+978 ] 0x0                (size_t) [0]
	[RSP+980 ] 0x0                (size_t) [0]
	[RSP+988 ] 0x0                (size_t) [0]
	[RSP+990 ] 0x0                (size_t) [0]
	[RSP+998 ] 0x0                (size_t) [0]
	[RSP+9A0 ] 0x0                (size_t) [0]
	[RSP+9A8 ] 0x25900000000      (void*)
	[RSP+9B0 ] 0x0                (size_t) [0]
	[RSP+9B8 ] 0x0                (size_t) [0]
	[RSP+9C0 ] 0x7FF6CDF70480     (void* -> SkyrimSE.exe+30B0480	add [rax], al)
	[RSP+9C8 ] 0x7FF6CDF73390     (void* -> SkyrimSE.exe+30B3390	add [rax], eax)
	[RSP+9D0 ] 0xDE43D0F5E0       (void*)
	[RSP+9D8 ] 0x40000000         (size_t) [1073741824]
	[RSP+9E0 ] 0x1                (size_t) [1]
	[RSP+9E8 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+9F0 ] 0x25BDDA34AF0      (void*)
	[RSP+9F8 ] 0x7FF6CB0872E0     (void* -> SkyrimSE.exe+01C72E0	xor edi, edi)
	[RSP+A00 ] 0x259230984F0      (BSResource::`anonymous namespace'::LooseFileStream*)
	[RSP+A08 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+A10 ] 0x3                (size_t) [3]
	[RSP+A18 ] 0x7FF600000001     (size_t) [140694538682369]
	[RSP+A20 ] 0x25BDDA34B00      (void*)
	[RSP+A28 ] 0x0                (size_t) [0]
	[RSP+A30 ] 0x259230984F0      (BSResource::`anonymous namespace'::LooseFileStream*)
	[RSP+A38 ] 0x259230984F0      (BSResource::`anonymous namespace'::LooseFileStream*)
	[RSP+A40 ] 0x259230F8968      (char*) "data\MESHES\dungeons\nordic\secretpass\animated\rmsmdoor02\norsecrmsmdoorsm02.nif"
	[RSP+A48 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+A50 ] 0x0                (size_t) [0]
	[RSP+A58 ] 0x7FF6CB087487     (void* -> SkyrimSE.exe+01C7487	lea rcx, [r15+0x168])
	[RSP+A60 ] 0x20000001         (size_t) [536870913]
	[RSP+A68 ] 0xA0000001         (size_t) [2684354561]
	[RSP+A70 ] 0x25BDDA34AF0      (void*)
	[RSP+A78 ] 0x7FF6CDF73390     (void* -> SkyrimSE.exe+30B3390	add [rax], eax)
	[RSP+A80 ] 0xDE20000000       (size_t) [954019610624]
	[RSP+A88 ] 0x25BDD8D1F78      (void*)
	[RSP+A90 ] 0x7FF6CDF703B0     (BSResource::EntryDB<BSModelDB::DBTraits>*)
	[RSP+A98 ] 0x25BDD8D1F78      (void*)
	[RSP+AA0 ] 0x0                (size_t) [0]
	[RSP+AA8 ] 0x7FF6CBC39960     (void* -> SkyrimSE.exe+0D79960	mov rcx, [rdi+0x08])
	[RSP+AB0 ] 0xDE43D0F700       (void*)
	[RSP+AB8 ] 0xDE43D0F5B0       (void*)
	[RSP+AC0 ] 0x7                (size_t) [7]
	[RSP+AC8 ] 0x25BDDA34CA0      (void*)
	[RSP+AD0 ] 0x7FF6CDF703B0     (BSResource::EntryDB<BSModelDB::DBTraits>*)
	[RSP+AD8 ] 0xDE43D0F688       (`IOManager::DoOnPreRunTask'::`2'::Pauser*)
	[RSP+AE0 ] 0x0                (size_t) [0]
	[RSP+AE8 ] 0x25A49FF41C8      (char*) "om Floor - Unofficial Skyrim Modders Patch.esp"
	[RSP+AF0 ] 0x0                (size_t) [0]
	[RSP+AF8 ] 0xDE43D0F720       (void*)
	[RSP+B00 ] 0x25A49FF4188      (void*)
	[RSP+B08 ] 0x7FF6CBC3A5B0     (void* -> SkyrimSE.exe+0D7A5B0	mov eax, [rsp+0x30])
	[RSP+B10 ] 0x25BDD8D23E0      (void*)
	[RSP+B18 ] 0xDE43D0F5B0       (void*)
	[RSP+B20 ] 0x7                (size_t) [7]
	[RSP+B28 ] 0x7FF6CBC37BD7     (void* -> SkyrimSE.exe+0D77BD7	cmp [rbx+0x1C], dil)
	[RSP+B30 ] 0x7FF6CDF70480     (void* -> SkyrimSE.exe+30B0480	add [rax], al)
	[RSP+B38 ] 0xDE43D0F688       (`IOManager::DoOnPreRunTask'::`2'::Pauser*)
	[RSP+B40 ] 0xE1               (size_t) [225]
	[RSP+B48 ] 0x1                (size_t) [1]
	[RSP+B50 ] 0x3                (size_t) [3]
	[RSP+B58 ] 0x7FF6CBB3DA0F     (void* -> SkyrimSE.exe+0C7DA0F	add r12d, eax)
	[RSP+B60 ] 0x25BDD8C8898      (BSTextureDB::QueuedHandles*)
	[RSP+B68 ] 0x7FF6CDF78750     (void* -> SkyrimSE.exe+30B8750	add [rax], al)
	[RSP+B70 ] 0x7FF6CDF78740     (void* -> SkyrimSE.exe+30B8740	cmp [rdi+0x7FF6CDF7], al)
	[RSP+B78 ] 0xDE43D0F720       (void*)
	[RSP+B80 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+B88 ] 0x7FF6CDF786E0     (BSResource::EntryDB<BSTextureDB::DBTraits>*)
	[RSP+B90 ] 0x0                (size_t) [0]
	[RSP+B98 ] 0xDE43D0F610       (void*)
	[RSP+BA0 ] 0x0                (size_t) [0]
	[RSP+BA8 ] 0x25A4A211200      (void*)
	[RSP+BB0 ] 0x4E20             (size_t) [20000]
	[RSP+BB8 ] 0x4C469078420      (size_t) [5241622201376]
	[RSP+BC0 ] 0x3                (size_t) [3]
	[RSP+BC8 ] 0x0                (size_t) [0]
	[RSP+BD0 ] 0x25A49FF41C8      (char*) "om Floor - Unofficial Skyrim Modders Patch.esp"
	[RSP+BD8 ] 0x7FF6CBC3681D     (void* -> SkyrimSE.exe+0D7681D	add rbx, 0x08)
	[RSP+BE0 ] 0x25A49FF4188      (void*)
	[RSP+BE8 ] 0xDE43D0F720       (void*)
	[RSP+BF0 ] 0x0                (size_t) [0]
	[RSP+BF8 ] 0x0                (size_t) [0]
	[RSP+C00 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+C08 ] 0x7FF6CC738D08     (void* -> SkyrimSE.exe+1878D08	loopne 0x00007FF6CC738D74)
	[RSP+C10 ] 0x25A4950C250      (BSTaskManagerThread*)
	[RSP+C18 ] 0x25A4950C250      (BSTaskManagerThread*)
	[RSP+C20 ] 0x25A4950C250      (BSTaskManagerThread*)
	[RSP+C28 ] 0x7FF6CBC3312F     (void* -> SkyrimSE.exe+0D7312F	mov [rbp+0x48], r12)
	[RSP+C30 ] 0x0                (size_t) [0]
	[RSP+C38 ] 0x0                (size_t) [0]
	[RSP+C40 ] 0xDE00000000       (size_t) [953482739712]
	[RSP+C48 ] 0x18C0             (size_t) [6336]
	[RSP+C50 ] 0x7FF6CDEC6801     (void* -> SkyrimSE.exe+3006801	add [rax], al)
	[RSP+C58 ] 0x259496839E8      (void*)
	[RSP+C60 ] 0xFFFFFFFFFFFFFFFE (size_t) [uint: 18446744073709551614 int: -2]
	[RSP+C68 ] 0x7FF6CC738818     (void* -> SkyrimSE.exe+1878818	xor [rsi], bh)
	[RSP+C70 ] 0x25900000000      (void*)
	[RSP+C78 ] 0x0                (size_t) [0]
	[RSP+C80 ] 0x0                (size_t) [0]
	[RSP+C88 ] 0x0                (size_t) [0]
	[RSP+C90 ] 0x0                (size_t) [0]
	[RSP+C98 ] 0x0                (size_t) [0]
	[RSP+CA0 ] 0x0                (size_t) [0]
	[RSP+CA8 ] 0x0                (size_t) [0]
	[RSP+CB0 ] 0x0                (size_t) [0]
	[RSP+CB8 ] 0x0                (size_t) [0]
	[RSP+CC0 ] 0x0                (size_t) [0]
	[RSP+CC8 ] 0x0                (size_t) [0]
	[RSP+CD0 ] 0x0                (size_t) [0]
	[RSP+CD8 ] 0x7FF6CBB05E4D     (void* -> SkyrimSE.exe+0C45E4D	mov rcx, [0x00007FF6CDEC6898])
	[RSP+CE0 ] 0x7FF6CDEC68F0     (void* -> SkyrimSE.exe+30068F0	add [rax], al)
	[RSP+CE8 ] 0x0                (size_t) [0]
	[RSP+CF0 ] 0x300002EB2002EB2  (size_t) [216172982668635826]
	[RSP+CF8 ] 0x25A4950C250      (BSTaskManagerThread*)
	[RSP+D00 ] 0x25A4950C250      (BSTaskManagerThread*)
	[RSP+D08 ] 0x0                (size_t) [0]
	[RSP+D10 ] 0x0                (size_t) [0]
	[RSP+D18 ] 0x7FFE438A7604     (void* -> KERNEL32.DLL+0017604	mov ecx, eax)
	[RSP+D20 ] 0x0                (size_t) [0]
	[RSP+D28 ] 0x0                (size_t) [0]
	[RSP+D30 ] 0x0                (size_t) [0]
	[RSP+D38 ] 0x0                (size_t) [0]
	[RSP+D40 ] 0x0                (size_t) [0]
	[RSP+D48 ] 0x7FFE457E26A1     (void* -> ntdll.dll+00526A1	jmp 0x00007FFE457E26C3)
	[RSP+D50 ] 0x0                (size_t) [0]
	[RSP+D58 ] 0x0                (size_t) [0]
	[RSP+D60 ] 0x0                (size_t) [0]
	[RSP+D68 ] 0x0                (size_t) [0]
	[RSP+D70 ] 0x0                (size_t) [0]
	[RSP+D78 ] 0x0                (size_t) [0]
	[RSP+D80 ] 0xBDE2643400000000 (size_t) [uint: 13682608792406065152 int: -4764135281303486464]
	[RSP+D88 ] 0x0                (size_t) [0]
	[RSP+D90 ] 0x0                (size_t) [0]
	[RSP+D98 ] 0x7FFE42FB7FE0     (void* -> KERNELBASE.dll+0117FE0	mov [rsp+0x10], rbx)
	[RSP+DA0 ] 0xDE43D0DB80       (void*)
	[RSP+DA8 ] 0x7FFEFF191BD4000  (size_t) [576443098137968640]
	[RSP+DB0 ] 0x7FFEFF191BD4     (size_t) [140733178256340]
	[RSP+DB8 ] 0xDE43D0DB80       (void*)
	[RSP+DC0 ] 0x0                (size_t) [0]
	[RSP+DC8 ] 0x0                (size_t) [0]
	[RSP+DD0 ] 0x0                (size_t) [0]
	[RSP+DD8 ] 0x0                (size_t) [0]
	[RSP+DE0 ] 0x0                (size_t) [0]
	[RSP+DE8 ] 0x0                (size_t) [0]
	[RSP+DF0 ] 0x0                (size_t) [0]
	[RSP+DF8 ] 0x0                (size_t) [0]
	[RSP+E00 ] 0x0                (size_t) [0]
	[RSP+E08 ] 0x0                (size_t) [0]
	[RSP+E10 ] 0x0                (size_t) [0]
	[RSP+E18 ] 0x0                (size_t) [0]
	[RSP+E20 ] 0x0                (size_t) [0]
	[RSP+E28 ] 0x0                (size_t) [0]
	[RSP+E30 ] 0x0                (size_t) [0]
	[RSP+E38 ] 0x0                (size_t) [0]
	[RSP+E40 ] 0x0                (size_t) [0]
	[RSP+E48 ] 0x0                (size_t) [0]
	[RSP+E50 ] 0x0                (size_t) [0]
	[RSP+E58 ] 0x0                (size_t) [0]
	[RSP+E60 ] 0x0                (size_t) [0]
	[RSP+E68 ] 0x0                (size_t) [0]
	[RSP+E70 ] 0x0                (size_t) [0]
	[RSP+E78 ] 0x0                (size_t) [0]
	[RSP+E80 ] 0x0                (size_t) [0]
	[RSP+E88 ] 0x0                (size_t) [0]
	[RSP+E90 ] 0x0                (size_t) [0]
	[RSP+E98 ] 0x0                (size_t) [0]
	[RSP+EA0 ] 0x0                (size_t) [0]
	[RSP+EA8 ] 0x0                (size_t) [0]
	[RSP+EB0 ] 0x0                (size_t) [0]
	[RSP+EB8 ] 0x0                (size_t) [0]
	[RSP+EC0 ] 0x0                (size_t) [0]
	[RSP+EC8 ] 0x0                (size_t) [0]
	[RSP+ED0 ] 0x0                (size_t) [0]
	[RSP+ED8 ] 0x0                (size_t) [0]
	[RSP+EE0 ] 0x0                (size_t) [0]
	[RSP+EE8 ] 0x0                (size_t) [0]
	[RSP+EF0 ] 0x0                (size_t) [0]
	[RSP+EF8 ] 0x0                (size_t) [0]
	[RSP+F00 ] 0x0                (size_t) [0]
	[RSP+F08 ] 0x0                (size_t) [0]
	[RSP+F10 ] 0x0                (size_t) [0]
	[RSP+F18 ] 0x0                (size_t) [0]
	[RSP+F20 ] 0x0                (size_t) [0]
	[RSP+F28 ] 0x0                (size_t) [0]
	[RSP+F30 ] 0x0                (size_t) [0]
	[RSP+F38 ] 0x0                (size_t) [0]
	[RSP+F40 ] 0x0                (size_t) [0]
	[RSP+F48 ] 0x0                (size_t) [0]
	[RSP+F50 ] 0x0                (size_t) [0]
	[RSP+F58 ] 0x0                (size_t) [0]
	[RSP+F60 ] 0x0                (size_t) [0]
	[RSP+F68 ] 0x0                (size_t) [0]
	[RSP+F70 ] 0x0                (size_t) [0]
	[RSP+F78 ] 0x0                (size_t) [0]
	[RSP+F80 ] 0x0                (size_t) [0]
	[RSP+F88 ] 0x0                (size_t) [0]
	[RSP+F90 ] 0x0                (size_t) [0]
	[RSP+F98 ] 0x0                (size_t) [0]
	[RSP+FA0 ] 0x0                (size_t) [0]
	[RSP+FA8 ] 0x0                (size_t) [0]
	[RSP+FB0 ] 0x0                (size_t) [0]
	[RSP+FB8 ] 0x0                (size_t) [0]
	[RSP+FC0 ] 0x0                (size_t) [0]
	[RSP+FC8 ] 0x0                (size_t) [0]
	[RSP+FD0 ] 0x0                (size_t) [0]
	[RSP+FD8 ] 0x0                (size_t) [0]
	[RSP+FE0 ] 0x0                (size_t) [0]
	[RSP+FE8 ] 0x0                (size_t) [0]
	[RSP+FF0 ] 0x0                (size_t) [0]
	[RSP+FF8 ] 0x0                (size_t) [0]
	[RSP+1000] 0x0                (size_t) [0]
	[RSP+1008] 0x0                (size_t) [0]
	[RSP+1010] 0x0                (size_t) [0]
	[RSP+1018] 0x0                (size_t) [0]
	[RSP+1020] 0x0                (size_t) [0]
	[RSP+1028] 0x0                (size_t) [0]
	[RSP+1030] 0x0                (size_t) [0]
	[RSP+1038] 0x0                (size_t) [0]
	[RSP+1040] 0x0                (size_t) [0]
	[RSP+1048] 0x0                (size_t) [0]
	[RSP+1050] 0x0                (size_t) [0]
	[RSP+1058] 0x0                (size_t) [0]
	[RSP+1060] 0x0                (size_t) [0]
	[RSP+1068] 0x0                (size_t) [0]
	[RSP+1070] 0x0                (size_t) [0]
	[RSP+1078] 0x0                (size_t) [0]
	[RSP+1080] 0x0                (size_t) [0]
	[RSP+1088] 0x0                (size_t) [0]
	[RSP+1090] 0x0                (size_t) [0]
	[RSP+1098] 0x0                (size_t) [0]
	[RSP+10A0] 0x0                (size_t) [0]
	[RSP+10A8] 0x0                (size_t) [0]
	[RSP+10B0] 0x0                (size_t) [0]
	[RSP+10B8] 0x0                (size_t) [0]
	[RSP+10C0] 0x0                (size_t) [0]
	[RSP+10C8] 0x0                (size_t) [0]
	[RSP+10D0] 0x0                (size_t) [0]
	[RSP+10D8] 0x0                (size_t) [0]
	[RSP+10E0] 0x0                (size_t) [0]
	[RSP+10E8] 0x0                (size_t) [0]
	[RSP+10F0] 0x0                (size_t) [0]
	[RSP+10F8] 0x0                (size_t) [0]
	[RSP+1100] 0x0                (size_t) [0]
	[RSP+1108] 0x0                (size_t) [0]
	[RSP+1110] 0x0                (size_t) [0]
	[RSP+1118] 0x0                (size_t) [0]
	[RSP+1120] 0x0                (size_t) [0]
	[RSP+1128] 0x0                (size_t) [0]
	[RSP+1130] 0x0                (size_t) [0]
	[RSP+1138] 0x0                (size_t) [0]
	[RSP+1140] 0x0                (size_t) [0]
	[RSP+1148] 0x0                (size_t) [0]
	[RSP+1150] 0x0                (size_t) [0]
	[RSP+1158] 0x0                (size_t) [0]
	[RSP+1160] 0x0                (size_t) [0]
	[RSP+1168] 0x0                (size_t) [0]
	[RSP+1170] 0x0                (size_t) [0]
	[RSP+1178] 0x0                (size_t) [0]
	[RSP+1180] 0x0                (size_t) [0]
	[RSP+1188] 0x0                (size_t) [0]
	[RSP+1190] 0x0                (size_t) [0]
	[RSP+1198] 0x0                (size_t) [0]
	[RSP+11A0] 0x0                (size_t) [0]
	[RSP+11A8] 0x0                (size_t) [0]
	[RSP+11B0] 0x0                (size_t) [0]
	[RSP+11B8] 0x0                (size_t) [0]
	[RSP+11C0] 0x0                (size_t) [0]
	[RSP+11C8] 0x0                (size_t) [0]
	[RSP+11D0] 0x0                (size_t) [0]
	[RSP+11D8] 0x0                (size_t) [0]
	[RSP+11E0] 0x0                (size_t) [0]
	[RSP+11E8] 0x0                (size_t) [0]
	[RSP+11F0] 0x0                (size_t) [0]
	[RSP+11F8] 0x0                (size_t) [0]
	[RSP+1200] 0x0                (size_t) [0]
	[RSP+1208] 0x0                (size_t) [0]
	[RSP+1210] 0x0                (size_t) [0]
	[RSP+1218] 0x0                (size_t) [0]
	[RSP+1220] 0x0                (size_t) [0]
	[RSP+1228] 0x0                (size_t) [0]
	[RSP+1230] 0x0                (size_t) [0]
	[RSP+1238] 0x0                (size_t) [0]
	[RSP+1240] 0x0                (size_t) [0]
	[RSP+1248] 0x0                (size_t) [0]
	[RSP+1250] 0x0                (size_t) [0]
	[RSP+1258] 0x0                (size_t) [0]
	[RSP+1260] 0x0                (size_t) [0]
	[RSP+1268] 0x0                (size_t) [0]
	[RSP+1270] 0x0                (size_t) [0]
	[RSP+1278] 0x0                (size_t) [0]
	[RSP+1280] 0x0                (size_t) [0]
	[RSP+1288] 0x0                (size_t) [0]
	[RSP+1290] 0x0                (size_t) [0]
	[RSP+1298] 0x0                (size_t) [0]
	[RSP+12A0] 0x0                (size_t) [0]
	[RSP+12A8] 0x0                (size_t) [0]
	[RSP+12B0] 0x0                (size_t) [0]
	[RSP+12B8] 0x0                (size_t) [0]
	[RSP+12C0] 0x0                (size_t) [0]
	[RSP+12C8] 0x0                (size_t) [0]
	[RSP+12D0] 0x0                (size_t) [0]
	[RSP+12D8] 0x0                (size_t) [0]
	[RSP+12E0] 0x0                (size_t) [0]
	[RSP+12E8] 0x0                (size_t) [0]
	[RSP+12F0] 0x0                (size_t) [0]
	[RSP+12F8] 0x0                (size_t) [0]
	[RSP+1300] 0x0                (size_t) [0]
	[RSP+1308] 0x0                (size_t) [0]
	[RSP+1310] 0x0                (size_t) [0]
	[RSP+1318] 0x0                (size_t) [0]
	[RSP+1320] 0x0                (size_t) [0]
	[RSP+1328] 0x0                (size_t) [0]
	[RSP+1330] 0x0                (size_t) [0]
	[RSP+1338] 0x0                (size_t) [0]
	[RSP+1340] 0x0                (size_t) [0]
	[RSP+1348] 0x0                (size_t) [0]
	[RSP+1350] 0x0                (size_t) [0]
	[RSP+1358] 0x0                (size_t) [0]
	[RSP+1360] 0x0                (size_t) [0]
	[RSP+1368] 0x0                (size_t) [0]
	[RSP+1370] 0x0                (size_t) [0]
	[RSP+1378] 0x0                (size_t) [0]
	[RSP+1380] 0x0                (size_t) [0]
	[RSP+1388] 0x0                (size_t) [0]
	[RSP+1390] 0x0                (size_t) [0]
	[RSP+1398] 0x0                (size_t) [0]
	[RSP+13A0] 0x0                (size_t) [0]
	[RSP+13A8] 0x0                (size_t) [0]
	[RSP+13B0] 0x0                (size_t) [0]
	[RSP+13B8] 0x0                (size_t) [0]
	[RSP+13C0] 0x0                (size_t) [0]
	[RSP+13C8] 0x0                (size_t) [0]
	[RSP+13D0] 0x0                (size_t) [0]
	[RSP+13D8] 0x0                (size_t) [0]
	[RSP+13E0] 0x0                (size_t) [0]
	[RSP+13E8] 0x0                (size_t) [0]
	[RSP+13F0] 0x0                (size_t) [0]
	[RSP+13F8] 0x0                (size_t) [0]
	[RSP+1400] 0x0                (size_t) [0]
	[RSP+1408] 0x0                (size_t) [0]
	[RSP+1410] 0x0                (size_t) [0]
	[RSP+1418] 0x0                (size_t) [0]
	[RSP+1420] 0x0                (size_t) [0]
	[RSP+1428] 0x0                (size_t) [0]
	[RSP+1430] 0x0                (size_t) [0]
	[RSP+1438] 0x0                (size_t) [0]
	[RSP+1440] 0x0                (size_t) [0]
	[RSP+1448] 0x0                (size_t) [0]
	[RSP+1450] 0x0                (size_t) [0]
	[RSP+1458] 0x0                (size_t) [0]
	[RSP+1460] 0x0                (size_t) [0]
	[RSP+1468] 0x0                (size_t) [0]
	[RSP+1470] 0x0                (size_t) [0]
	[RSP+1478] 0x0                (size_t) [0]
	[RSP+1480] 0x0                (size_t) [0]
	[RSP+1488] 0x0                (size_t) [0]
	[RSP+1490] 0x0                (size_t) [0]
	[RSP+1498] 0x0                (size_t) [0]
	[RSP+14A0] 0x0                (size_t) [0]
	[RSP+14A8] 0x0                (size_t) [0]
	[RSP+14B0] 0x0                (size_t) [0]
	[RSP+14B8] 0x0                (size_t) [0]
	[RSP+14C0] 0x0                (size_t) [0]
	[RSP+14C8] 0x0                (size_t) [0]
	[RSP+14D0] 0x0                (size_t) [0]
	[RSP+14D8] 0x0                (size_t) [0]
	[RSP+14E0] 0x0                (size_t) [0]
	[RSP+14E8] 0x0                (size_t) [0]
	[RSP+14F0] 0x0                (size_t) [0]
	[RSP+14F8] 0x0                (size_t) [0]
	[RSP+1500] 0x0                (size_t) [0]
	[RSP+1508] 0x0                (size_t) [0]
	[RSP+1510] 0x0                (size_t) [0]
	[RSP+1518] 0x0                (size_t) [0]
	[RSP+1520] 0x0                (size_t) [0]
	[RSP+1528] 0x0                (size_t) [0]
	[RSP+1530] 0x0                (size_t) [0]
	[RSP+1538] 0x0                (size_t) [0]
	[RSP+1540] 0x0                (size_t) [0]
	[RSP+1548] 0x0                (size_t) [0]
	[RSP+1550] 0x0                (size_t) [0]
	[RSP+1558] 0x0                (size_t) [0]
	[RSP+1560] 0x0                (size_t) [0]
	[RSP+1568] 0x0                (size_t) [0]
	[RSP+1570] 0x0                (size_t) [0]
	[RSP+1578] 0x0                (size_t) [0]

MODULES:
	XINPUT1_3.dll                     0x000000400000
	steam_api64.dll                   0x000052BB0000
	X3DAudio1_7.dll                   0x000052BF0000
	d3d11.dll                         0x000180000000
	clbcatq.dll                       0x02592A7B0000
	bcryptPrimitives.dll              0x02593DB20000
	PayloadInterpreter.dll            0x025961650000
	SkyrimSE.exe                      0x7FF6CAEC0000
	nvwgf2umx.dll                     0x7FFDA24A0000
	libxess.dll                       0x7FFDCFCA0000
	D3D12Core.dll                     0x7FFDED310000
	DSOUND.DLL                        0x7FFDF90D0000
	nvspcap64.dll                     0x7FFDF9A70000
	dxilconv.dll                      0x7FFDF9DA0000
	XAudio2_7.dll                     0x7FFDFA0D0000
	d3dcompiler_46e.dll               0x7FFDFA670000
	gameoverlayrenderer64.dll         0x7FFDFAA30000
	Twilight.dll                      0x7FFDFAD70000
	TrueHUD.dll                       0x7FFDFADE0000
	TrueDirectionalMovement.dll       0x7FFDFAEA0000
	TK_Dodge_RE.dll                   0x7FFDFAF60000
	SSMT_Fix.dll                      0x7FFDFAFC0000
	SSEReShadeHelper.dll              0x7FFDFB030000
	SSEDisplayTweaks.dll              0x7FFDFB090000
	SoundRecordDistributor.dll        0x7FFDFB140000
	SoftShadows.dll                   0x7FFDFB220000
	SmoothCam.dll                     0x7FFDFB2D0000
	PDPerfPlugin.dll                  0x7FFDFB440000
	ffx_fsr2_api_dx12_x64.dll         0x7FFDFB4A0000
	SkyrimUpscaler.dll                0x7FFDFB770000
	SkyrimOutfitSystemSE.dll          0x7FFDFB8B0000
	skee64.dll                        0x7FFDFBAA0000
	SimpleDualSheath.dll              0x7FFDFBCB0000
	ShowPlayerInMenus.dll             0x7FFDFBD50000
	ShadowBoost.dll                   0x7FFDFBDC0000
	ShaderTools.dll                   0x7FFDFBE80000
	Recipes.dll                       0x7FFDFBF20000
	QuickLootRE.dll                   0x7FFDFC010000
	Precision.dll                     0x7FFDFC160000
	ScrambledBugs.dll                 0x7FFDFC3B0000
	po3_Tweaks.dll                    0x7FFDFC450000
	po3_SpellPerkItemDistributor.dll  0x7FFDFC520000
	po3_MoonMod.dll                   0x7FFDFC690000
	po3_LockVariations.dll            0x7FFDFC740000
	po3_KeywordItemDistributor.dll    0x7FFDFC7F0000
	po3_ConsolePlusPlus.dll           0x7FFDFC8E0000
	po3_BaseObjectSwapper.dll         0x7FFDFC990000
	PapyrusUtil.dll                   0x7FFDFCB20000
	PAPER.dll                         0x7FFDFCC90000
	mfgfix.dll                        0x7FFDFCD10000
	MergeMapper.dll                   0x7FFDFCD80000
	MCMHelper.dll                     0x7FFDFCE60000
	LocationalEncounterZones.dll      0x7FFDFCF40000
	Kaputt.dll                        0x7FFDFD020000
	JContainers64.dll                 0x7FFDFD120000
	InventoryInjector.dll             0x7FFDFD400000
	InfinityUI.dll                    0x7FFDFD4A0000
	ImmersiveEquipmentDisplays.dll    0x7FFDFD5D0000
	htfq_se.dll                       0x7FFDFDA50000
	hdtSMP64.dll                      0x7FFDFDAB0000
	HDT-SMP Force Fields.dll          0x7FFDFE2E0000
	Fuz Ro D'oh.dll                   0x7FFDFE370000
	FaceGenFixes.dll                  0x7FFDFE3E0000
	Experience.dll                    0x7FFDFE450000
	ENBInputDisabler.dll              0x7FFDFE620000
	ENBHelperSE.dll                   0x7FFDFE6C0000
	DynDOLOD.DLL                      0x7FFDFE760000
	DynamicCollisionAdjustment.dll    0x7FFDFE7C0000
	DynamicAnimationReplacer.dll      0x7FFDFE830000
	DtryKeyUtil.dll                   0x7FFDFE8A0000
	CrashLogger.dll                   0x7FFDFE910000
	ConsoleUtilSSE.dll                0x7FFDFEBD0000
	CompassNavigationOverhaul.dll     0x7FFDFEC70000
	CommunityShaders.dll              0x7FFDFEE00000
	CombatMusicFix.dll                0x7FFDFEF20000
	cbp.dll                           0x7FFDFEFB0000
	Cathub.dll                        0x7FFDFF0B0000
	BugFixesSSE.dll                   0x7FFDFF1B0000
	BetterThirdPersonSelection.dll    0x7FFDFF240000
	BehaviorDataInjector.dll          0x7FFDFF450000
	AutoParallax.dll                  0x7FFDFF5B0000
	CameraShake.dll                   0x7FFE00950000
	autoBodyAE.dll                    0x7FFE009C0000
	steamclient64.dll                 0x7FFE00A50000
	dxgi.dll                          0x7FFE02010000
	ArcheryRebalance.dll              0x7FFE06370000
	AnimationMotionRevolution.dll     0x7FFE06620000
	ArcheryLocationalDamage.dll       0x7FFE07C90000
	DualWieldParryingSKSE.dll         0x7FFE08160000
	AnimationQueueFix.dll             0x7FFE081C0000
	tier0_s64.dll                     0x7FFE08230000
	AHZmoreHUDPlugin.dll              0x7FFE08590000
	DialogueMovementEnabler.dll       0x7FFE089D0000
	AHZmoreHUDInventory.dll           0x7FFE08A70000
	AddItemMenuSE.dll                 0x7FFE08AE0000
	EngineFixes.dll                   0x7FFE09240000
	ActorLimitFix.dll                 0x7FFE09B30000
	tbbmalloc.dll                     0x7FFE0D3D0000
	vstdlib_s64.dll                   0x7FFE0D440000
	D3DCOMPILER_43.dll                0x7FFE0D500000
	nvldumdx.dll                      0x7FFE0D770000
	usvfs_x64.dll                     0x7FFE0DDB0000
	D3DSCache.dll                     0x7FFE0E290000
	StormLightning.dll                0x7FFE0E8E0000
	mskeyprotect.dll                  0x7FFE10380000
	ncryptsslp.dll                    0x7FFE10440000
	XInput1_4.dll                     0x7FFE10870000
	ondemandconnroutehelper.dll       0x7FFE13C00000
	BetterJumpingSE.dll               0x7FFE15290000
	Windows.UI.dll                    0x7FFE22850000
	AlternateConversationCamera.dll   0x7FFE22B70000
	inputhost.dll                     0x7FFE238A0000
	tbb.dll                           0x7FFE23AE0000
	skse64_1_6_640.dll                0x7FFE23B50000
	d3dx11_43.dll                     0x7FFE23C80000
	bink2w64.dll                      0x7FFE23CD0000
	textinputframework.dll            0x7FFE24620000
	OneCoreCommonProxyStub.dll        0x7FFE27640000
	Secur32.dll                       0x7FFE2C7D0000
	XeFX.dll                          0x7FFE2D8E0000
	dbgcore.DLL                       0x7FFE2DC30000
	VCRUNTIME140.dll                  0x7FFE2E1E0000
	MSVCP140.dll                      0x7FFE2E200000
	webio.dll                         0x7FFE2ED20000
	WININET.dll                       0x7FFE2F8F0000
	winmmbase.dll                     0x7FFE30050000
	VCRUNTIME140_1.dll                0x7FFE300F0000
	iertutil.dll                      0x7FFE30450000
	srvcli.dll                        0x7FFE30710000
	urlmon.dll                        0x7FFE30740000
	dbghelp.dll                       0x7FFE309E0000
	WINMM.dll                         0x7FFE31320000
	xinput9_1_0.dll                   0x7FFE31B70000
	MpOav.dll                         0x7FFE32990000
	amsi.dll                          0x7FFE32A80000
	d3d12.dll                         0x7FFE32B40000
	AchievementsModsEnabler.dll       0x7FFE32BA0000
	EVLaS.dll                         0x7FFE32BF0000
	XeFX_Loader.dll                   0x7FFE32C50000
	DINPUT8.dll                       0x7FFE32C60000
	wbemsvc.dll                       0x7FFE32FD0000
	fastprox.dll                      0x7FFE33250000
	igc64.dll                         0x7FFE33F90000
	wbemcomn.dll                      0x7FFE362F0000
	igdgmm64.dll                      0x7FFE36380000
	fwpuclnt.dll                      0x7FFE364A0000
	igd10iumd64.dll                   0x7FFE366E0000
	dxcore.dll                        0x7FFE37E70000
	OneCoreUAPCommonProxyStub.dll     0x7FFE390E0000
	rasadhlp.dll                      0x7FFE39F10000
	wbemprox.dll                      0x7FFE39F20000
	WINHTTP.dll                       0x7FFE39F50000
	MMDevApi.dll                      0x7FFE3A990000
	AUDIOSES.DLL                      0x7FFE3AA70000
	WindowsCodecs.dll                 0x7FFE3AD00000
	dhcpcsvc6.DLL                     0x7FFE3B110000
	drvstore.dll                      0x7FFE3B1C0000
	cryptnet.dll                      0x7FFE3B360000
	dhcpcsvc.DLL                      0x7FFE3B3A0000
	WindowManagementAPI.dll           0x7FFE3B4F0000
	VERSION.dll                       0x7FFE3C1D0000
	WINNSI.DLL                        0x7FFE3C330000
	MSVCP140_ATOMIC_WAIT.dll          0x7FFE3C470000
	avrt.dll                          0x7FFE3CBF0000
	AchievementsModsEnablerLoader.dll 0x7FFE3CE40000
	ffx_fsr2_api_x64.dll              0x7FFE3CF40000
	twinapi.appcore.dll               0x7FFE3D3C0000
	d3dx9_42.dll                      0x7FFE3DCA0000
	PROPSYS.dll                       0x7FFE3E590000
	d3d11.dll                         0x7FFE3F130000
	D3DCOMPILER_47.dll                0x7FFE3F3A0000
	wintypes.dll                      0x7FFE3F900000
	dcomp.dll                         0x7FFE3FBB0000
	CoreUIComponents.dll              0x7FFE40120000
	CoreMessaging.dll                 0x7FFE40580000
	apphelp.dll                       0x7FFE406B0000
	uxtheme.dll                       0x7FFE407A0000
	resourcepolicyclient.dll          0x7FFE40970000
	dwmapi.dll                        0x7FFE40A70000
	kernel.appcore.dll                0x7FFE40D60000
	windows.storage.dll               0x7FFE40F60000
	HID.DLL                           0x7FFE41700000
	dxgi.dll                          0x7FFE41880000
	schannel.DLL                      0x7FFE41E30000
	rsaenh.dll                        0x7FFE41F10000
	ntmarta.dll                       0x7FFE42050000
	UMPDC.dll                         0x7FFE422E0000
	IPHLPAPI.DLL                      0x7FFE42300000
	DNSAPI.dll                        0x7FFE42340000
	netutils.dll                      0x7FFE42460000
	powrprof.dll                      0x7FFE42470000
	MSWSOCK.dll                       0x7FFE42660000
	CRYPTSP.dll                       0x7FFE42850000
	CRYPTBASE.DLL                     0x7FFE42870000
	Wldp.dll                          0x7FFE42900000
	NTASN1.dll                        0x7FFE42930000
	ncrypt.dll                        0x7FFE42970000
	msasn1.dll                        0x7FFE42A90000
	devobj.dll                        0x7FFE42C50000
	DPAPI.DLL                         0x7FFE42CA0000
	SSPICLI.DLL                       0x7FFE42D60000
	USERENV.dll                       0x7FFE42DA0000
	profapi.dll                       0x7FFE42DE0000
	KERNELBASE.dll                    0x7FFE42EA0000
	bcrypt.dll                        0x7FFE43180000
	WINTRUST.DLL                      0x7FFE43260000
	CRYPT32.dll                       0x7FFE432D0000
	msvcp_win.dll                     0x7FFE43430000
	win32u.dll                        0x7FFE434D0000
	gdi32full.dll                     0x7FFE43500000
	ucrtbase.dll                      0x7FFE43610000
	cfgmgr32.dll                      0x7FFE43710000
	sechost.dll                       0x7FFE437F0000
	KERNEL32.DLL                      0x7FFE43890000
	USER32.dll                        0x7FFE43950000
	msvcrt.dll                        0x7FFE43AF0000
	SHCORE.dll                        0x7FFE43DA0000
	ole32.dll                         0x7FFE43E50000
	SHLWAPI.dll                       0x7FFE43F80000
	NSI.dll                           0x7FFE43FE0000
	IMM32.DLL                         0x7FFE43FF0000
	imagehlp.dll                      0x7FFE44020000
	RPCRT4.dll                        0x7FFE44040000
	combase.dll                       0x7FFE44170000
	WS2_32.dll                        0x7FFE44580000
	PSAPI.DLL                         0x7FFE44600000
	SETUPAPI.dll                      0x7FFE44690000
	ADVAPI32.dll                      0x7FFE44BF0000
	OLEAUT32.dll                      0x7FFE44CA0000
	GDI32.dll                         0x7FFE44EB0000
	SHELL32.dll                       0x7FFE44EE0000
	MSCTF.dll                         0x7FFE45630000
	ntdll.dll                         0x7FFE45790000

SKSE PLUGINS:
	AchievementsModsEnablerLoader.dll v1.2
	ActorLimitFix.dll
	AddItemMenuSE.dll
	AHZmoreHUDInventory.dll v2.1.2
	AHZmoreHUDPlugin.dll v5.2.2
	AlternateConversationCamera.dll
	AnimationMotionRevolution.dll
	AnimationQueueFix.dll v1.0.1
	ArcheryLocationalDamage.dll v2.1.1
	ArcheryRebalance.dll v1
	autoBodyAE.dll
	AutoParallax.dll v1.0.7
	BehaviorDataInjector.dll v0.1.3
	BetterJumpingSE.dll
	BetterThirdPersonSelection.dll v1
	BugFixesSSE.dll
	CameraShake.dll v1
	Cathub.dll v1.6
	cbp.dll
	CombatMusicFix.dll v1.0.1
	CommunityShaders.dll v0.1
	CompassNavigationOverhaul.dll
	ConsoleUtilSSE.dll v1.4
	CrashLogger.dll v1.8
	DialogueMovementEnabler.dll v2.2
	DtryKeyUtil.dll v0.0.2
	DualWieldParryingSKSE.dll v1.3
	DynamicAnimationReplacer.dll v1.1.3
	DynamicCollisionAdjustment.dll v1.1
	DynDOLOD.DLL v2.45
	ENBHelperSE.dll v2.2
	ENBInputDisabler.dll v1.0.2
	EngineFixes.dll v6.1.1
	EVLaS.dll v1.3.1
	Experience.dll v3.1
	FaceGenFixes.dll v1.0.3
	Fuz Ro D'oh.dll v2.3.6.1030
	HDT-SMP Force Fields.dll
	hdtSMP64.dll
	htfq_se.dll v2
	ImmersiveEquipmentDisplays.dll v1.6.3
	InfinityUI.dll
	InventoryInjector.dll v1.0.2
	JContainers64.dll v4.2.3
	Kaputt.dll v1.2.6
	LocationalEncounterZones.dll v1.0.2
	MCMHelper.dll v1.4
	MergeMapper.dll v1.4
	mfgfix.dll v1.6.1
	PAPER.dll v2.2.3
	PapyrusUtil.dll
	PayloadInterpreter.dll v1
	po3_BaseObjectSwapper.dll v2.5.1.1
	po3_ConsolePlusPlus.dll v1.1.0.1
	po3_KeywordItemDistributor.dll v2.2.0.1
	po3_LockVariations.dll v3.1.0.1
	po3_MoonMod.dll v2.0.2.1
	po3_SpellPerkItemDistributor.dll v6.6.1.1
	po3_Tweaks.dll v1.8.0.1
	Precision.dll v2.0.4
	QuickLootRE.dll v2.14.2
	Recipes.dll v1.1
	ScrambledBugs.dll
	ShaderTools.dll
	ShadowBoost.dll
	ShowPlayerInMenus.dll v2.0.2
	SimpleDualSheath.dll v1.5.6
	skee64.dll
	SkyrimOutfitSystemSE.dll v0.6
	SkyrimUpscaler.dll v1
	SmoothCam.dll
	SoftShadows.dll v1.2
	SoundRecordDistributor.dll v1.2
	SSEDisplayTweaks.dll v0.5.12
	SSEReShadeHelper.dll v1
	SSMT_Fix.dll v1.0.2
	StormLightning.dll
	TK_Dodge_RE.dll
	TrueDirectionalMovement.dll v2.2.3
	TrueHUD.dll v1.1.8
	Twilight.dll v1.1

PLUGINS:
	Light: 126	Regular: 231	Total: 357
	[00]     Skyrim.esm
	[01]     Update.esm
	[02]     Dawnguard.esm
	[03]     HearthFires.esm
	[04]     Dragonborn.esm
	[05]     ccBGSSSE001-Fish.esm
	[06]     ccBGSSSE025-AdvDSGS.esm
	[07]     Unofficial Skyrim Special Edition Patch.esp
	[08]     Unofficial Skyrim Modders Patch.esp
	[09]     Skyrim Project Optimization - Full Version.esm
	[0A]     Paraphernalia Anti-Flicker.esp
	[0B]     Occ_Skyrim_Tamriel.esp
	[0C]     _Natural Waterfalls.esp
	[0D]     arnima.esm
	[0E]     BSAssets.esm
	[0F]     BSHeartland.esm
	[10]     BS_DLC_patch.esp
	[11]     High Poly Head.esm
	[12]     Penitus_Oculatus.esp
	[13]     PrvtI_LunarArmory.esp
	[14]     Campfire.esm
	[15]     RaceCompatibility.esm
	[16]     Vigilant.esm
	[17]     Chanterelle World.esp
	[18]     Apachii_DivineEleganceStore.esm
	[19]     DynDOLOD.esm
	[1A]     SkyUI_SE.esp
	[1B]     Lore Weapon Expansion - Daedric Crescent.esp
	[1C]     Lore Weapon Expansion - Goldbrand.esp
	[1D]     Lore Weapon Expansion - Relics of the Crusader.esp
	[1E]     SMIM-SE-Merged-All.esp
	[1F]     Audio Overhaul Skyrim.esp
	[20]     Mortal Enemies.esp
	[21]     Immersive Sounds - Compendium.esp
	[22]     UIExtensions.esp
	[23]     AddItemMenuSE.esp
	[24]     EnhancedLightsandFX.esp
	[25]     tpos_complete02_RTCWG.esp
	[26]     RelightingSkyrim_SSE.esp
	[27]     Thaumaturgy.esp
	[28]     Weapons Armor Clothing & Clutter Fixes.esp
	[29]     VisualAnimatedEnchants2023.esp
	[2A]     RaceMenu.esp
	[2B]     RaceMenuHH.esp
	[2C]     RaceMenuPlugin.esp
	[2D]     TKDodge.esp
	[2E]     iHUD.esp
	[2F]     QuickLight.esp
	[30]     XPMSE.esp
	[31]     FNIS.esp
	[32]     BlendedRoads.esp
	[33]     KS Hairdo's.esp
	[34]     RLO - Effects.esp
	[35]     Footprints.esp
	[36]     SMIM-Bruma-Patch.esp
	[37]     SkyrimOutfitSystem.esp
	[38]     Marfleet's Loading Screens.esp
	[39]     20 More Perk Points.esp
	[3A]     Brows.esp
	[3B]     Extended Encounters.esp
	[3C]     FMS_FemaleMakeupSuite.esp
	[3D]     Book Of Shadows.esp
	[3E]     FaceSculptorsRacemenu.esp
	[3F]     ChanterelleNVM.esp
	[40]     ELFX - Exteriors.esp
	[41]     ESOimports.esp
	[42]     DepthsOfSkyrim.esp
	[43]     Modpocalypse NPCs (v3) SSE.esp
	[44]     Summermyst - Enchantments of Skyrim.esp
	[45]     Summermyst - WACCF Patch.esp
	[46]     Immersive Weapons.esp
	[47]     COTN - Falkreath.esp
	[48]     The Blackest Reaches.esp
	[49]     COTN - Dawnstar.esp
	[4A]     Medieval Lanterns of Skyrim.esp
	[4B]     COTN - Morthal.esp
	[4C]     Eli_Skaal Village Overhaul.esp
	[4D]     GodsAndWorship.esp
	[4E]     COTN - Winterhold.esp
	[4F]     AI Overhaul.esp
	[50]     Cutting Room Floor.esp
	[51]     Obsidian Mountain Fogs.esp
	[52]     DeadlySpellImpacts.esp
	[53]     RLO - Illuminated Spells.esp
	[54]     Apothecary.esp
	[55]     Ish's Respec Mod.esp
	[56]     Riverwood_By_Nesbit.esp
	[57]     PaintitBlack.esp
	[58]     OBIS SE.esp
	[59]     EVGATAIO.esp
	[5A]     Immersive Encounters.esp
	[5B]     SeranaDialogAddon.esp
	[5C]     OBIS Loot SE.esp
	[5D]     Embers XD.esp
	[5E]     Reliquary of Myth.esp
	[5F]     DIS_Replacer.esp
	[60]     Odin - Skyrim Magic Overhaul.esp
	[61]     SkyTEST-RealisticAnimals&Predators.esp
	[62]     ForcefulTongue.esp
	[63]     Hunterborn.esp
	[64]     ApothecaryFood.esp
	[65]     Race Compatibility Dialogue SSE.esp
	[66]     AVExpansion.esp
	[67]     Hothtrooper44_ArmorCompilation.esp
	[68]     Realm of Lorkhan - Custom Alternate Start - Choose your own adventure.esp
	[69]     CompanionsTweaks.esp
	[6A]     Guard Dialogue Overhaul.esp
	[6B]     Hothtrooper44_Armor_Ecksstra.esp
	[6C]     DIS_Armor_Compilation.esp
	[6D]     Point The Way.esp
	[6E]     Realm of Lorkhan - My Edits.esp
	[6F]     Sea of Spirits.esp
	[70]     Skyrim Dreams & Nightmares(Personalized Music plugin).esp
	[71]     Symphonic Soundtrack v2HQ - Replacement.esp
	[72]     NyghtfallMM.esp
	[73]     DetLight.esp
	[74]     PrvtI_HeavyArmory.esp
	[75]     Lit Road Signs.esp
	[76]     man_DaedricShrines.esp
	[77]     ZIA_Complete Pack.esp
	[78]     Tel Mithryn.esp
	[79]     Valravn - Integrated Combat of Skyrim.esp
	[7A]     VioLens SE.esp
	[7B]     Lore Weapon Expansion.esp
	[7C]     UniqueBorderGates-All.esp
	[7D]     AHZBetterDGEntranceSE.esp
	[7E]     Shiva's Vanilla Clothing Replacer.esp
	[7F]     Tools of Kagrenac.esp
	[80]     ESOImports - ToK Patch.esp
	[81]     hokoronenemies.esp
	[82]     Arcanum.esp
	[83]     ORI - HarkonSword.esp
	[84]     GargoyleBlood.esp
	[85]     earthquakes - MCM.esp
	[86]     IcePenguinWorldMap.esp
	[87]     TheEyesOfBeauty.esp
	[88]     autoBodyAE.esp
	[89]     SnuSnu-VioLensed.esp
	[8A]     SprintSlide.esp
	[8B]     ZMD'S Gothic Tattoos Race Menu CBBE v1.esp
	[8C]     SFO_SkinFeatureOverlays.esp
	[8D]     NB-Scars.esp
	[8E]     LockRelatedLoot.esp
	[8F]     ImmersiveInteractions.esp
	[90]     Air Dash.esp
	[91]     SRE.esp
	[92]     Unlucky Loot.esp
	[93]     KaputtVanillaKillmoves.esp
	[94]     Trample Killmove.esp
	[95]     SwampWater.esp
	[96]     BlueKind.esp
	[97]     DawnguardArsenal.esp
	[98]     Player Size Adjuster.esp
	[99]     Unique Uniques.esp
	[9A]     AltairNightingale.esp
	[9B]     ogSplendorDragons.esp
	[9C]     SkyHUD.esp
	[9D]     Cathedral - 3D Pine Grass.esp
	[9E]     ScrimshawExpanded.esp
	[9F]     Origins Of Forest - 3D Forest Grass.esp
	[A0]     Smilodon - Combat of Skyrim.esp
	[A1]     dD - Enhanced Blood Main.esp
	[A2]     dD-Medium Script Range.esp
	[A3]     Predator Vision.esp
	[A4]     Aequinoctium.esp
	[A5]     Aequinoctium - BSBruma PATCH.esp
	[A6]     NoldorArmor.esp
	[A7]     The Eyes Of Beauty - Elves Edition.esp
	[A8]     AMatterOfTime.esp
	[A9]     Race Compatibility Dialogue SSE - Bruma.esp
	[AA]     IHSS.esp
	[AB]     TB'sImprovedWater.esp
	[AC]     Spaghetti's Cities Merged.esp
	[AD]     LokiHorses.esp
	[AE]     SkySprint.esp
	[AF]     SignatureEquipment.esp
	[B0]     MidAirShouts.esp
	[B1]     Nocollision_clutter.esp
	[B2]     Mid Air Whirlwind Sprint.esp
	[B3]     RaceCompatibilityUSKPOverride.esp
	[B4]     DBVO_Base.esp
	[B5]     DBVO_VoicePack_Ciri_Skyrim.esp
	[B6]     SDA Campfire Patch.esp
	[B7]     Race Compatibility Dialogue SSE - Beyond Reach.esp
	[B8]     Backshields.esp
	[B9]     ACatsLife.esp
	[BA]     Frostfall.esp
	[BB]     DragonAgeWeapons.esp
	[BC]     Apachii_DivineEleganceStore_Patch.esp
	[BD]     Cityside.esp
	[BE]     ThievesGuildLadder.esp
	[BF]     High Poly Head Vampire Fix.esp
	[C0]     The Lost Masks.esp
	[C1]     mihailfleshatronach.esp
	[C2]     GrimmerReaper.esp
	[C3]     mihailgiantesses.esp
	[C4]     nesbits_skyrim_bridges.esp
	[C5]     CarriageStationsTowns.esp
	[C6]     CuttingStoneCorners.esp
	[C7]     RAO - ELFX Patch.esp
	[C8]     AHZBetterDGEntranceSE-ELFXPatch.esp
	[C9]     VFWC.esp
	[CA]     PrvtIRoyalArmory.esp
	[CB]     WetandCold.esp
	[CC]     IMAGINATOR SSE - Visual Control for Skyrim.esp
	[CD]     SignpostFastTravel.esp
	[CE]     Skyshards.esp
	[CF]     Dark Dreams.esp
	[D0]     Immersive Speechcraft.esp
	[D1]     mihaildwarvenpowerarmor.esp
	[D2]     mihailweepingstalkers.esp
	[D3]     NewDogsReplacers.esp
	[D4]     Tanning And Smelting Experience.esp
	[D5]     Vanilla hair remake SMP.esp
	[D6]     Imperious - Races of Skyrim.esp
	[D7]     Racial Body Morphs - Extreme Morphs - Imperious.esp
	[D8]     Trade & Barter.esp
	[D9]     Ordinator - Perks of Skyrim.esp
	[DA]     Odin - Ordinator Compatibility Patch.esp
	[DB]     Immersive Citizens - AI Overhaul.esp
	[DC]     Relationship Dialogue Overhaul.esp
	[DD]     Castle Volkihar Rebuilt.esp
	[DE]     fortdawnguardimmersive.esp
	[DF]     RDO - CRF + USSEP Patch.esp
	[E0]     The Brotherhood of Old.esp
	[E1]     CFTO.esp
	[E2]     CFTO - Immersive Citizens Patch.esp
	[E3]     Convenient Horses.esp
	[E4]     SDA Convenient Horses Patch.esp
	[E5]     Race Compatibility Dialogue SSE - RDO.esp
	[E6]     DynDOLOD.esp
	[FE:000] ccQDRSSE001-SurvivalMode.esl
	[FE:001] ccBGSSSE037-Curios.esl
	[FE:002] Paraphernalia Anti-Flicker AIO.esp
	[FE:003] Landscape and Water Fixes.esp
	[FE:004] Navigator-NavFixes.esl
	[FE:005] AHZmoreHUD.esl
	[FE:006] AHZmoreHUDInventory.esl
	[FE:007] DynamicCollisionAdjustment.esl
	[FE:008] wkup.esm
	[FE:009] Experience.esl
	[FE:00A] TrueHUD.esl
	[FE:00B] SmoothCam.esl
	[FE:00C] EVGAnimatedTraversal.esl
	[FE:00D] Expressive Facegen Morphs.esl
	[FE:00E] Vanilla Scripts Enhanced.esl
	[FE:00F] 1Markynaz.esl
	[FE:010] Occ_Skyrim_AnniversaryFreeCC.esp
	[FE:011] Legendary Elder Scrolls Loading Screen.esl
	[FE:012] TESLoadingScreen1.esl
	[FE:013] VigilantHiResPackSE.esl
	[FE:014] ClassicClassesReimagined.esm
	[FE:015] Reverb and Ambiance Overhaul - Skyrim.esp
	[FE:016] AOS_ISC_Integration.esp
	[FE:017] CBBE.esp
	[FE:018] MCMHelper.esp
	[FE:019] StormLightning.esp
	[FE:01A] Bandit Lines Expansion.esp
	[FE:01B] Dirt and Blood - Dynamic Visuals.esp
	[FE:01C] Bruma Bears of the North Patch.esp
	[FE:01D] Precision.esp
	[FE:01E] ShowPlayerInMenus.esp
	[FE:01F] Disable Turn Animation.esp
	[FE:020] SmoothJumpINISettings.esp
	[FE:021] Keytrace.esp
	[FE:022] Perks from Questing.esp
	[FE:023] Harder Thaneships.esp
	[FE:024] Arena.esp
	[FE:025] Realistic AI Detection 3 - Lite.esp
	[FE:026] AdditionalRecipes.esp
	[FE:027] aMidianBorn_Book of Silence.esp
	[FE:028] TrueDirectionalMovement.esp
	[FE:029] dD-No Spinning Death Animation.esp
	[FE:02A] DynamicWait.esp
	[FE:02B] KSHairdosSMP.esp
	[FE:02C] Mining360.esp
	[FE:02D] BetterThirdPersonSelection.esp
	[FE:02E] Thaumaturgy_WACCF.esp
	[FE:02F] ELFX Fixes.esp
	[FE:030] [xPatch] Modpocalypse NPCs (v3) SSE - AI Overhaul.esp
	[FE:031] Apothecary - Bruma Patch.esp
	[FE:032] Apothecary - Fishing Patch.esp
	[FE:033] Apothecary - Saints & Seducers Patch.esp
	[FE:034] Ambiance.esp
	[FE:035] COTN Dawnstar - ELFX Inclusive Patch.esp
	[FE:036] [xPatch] Modpocalypse NPCs (v3) SSE - OBIS SE.esp
	[FE:037] OBIS WACCF Patch.esp
	[FE:038] COTN Falkreath - ELFX Patch.esp
	[FE:039] COTN Winterhold - ELFX Patch.esp
	[FE:03A] Bears of the North.esp
	[FE:03B] SkyTest Bears of the North Patch.esp
	[FE:03C] ApothecaryFood - Bruma Patch.esp
	[FE:03D] ApothecaryFood - Fishing Patch.esp
	[FE:03E] ApothecaryFood - USSEP Patch.esp
	[FE:03F] RoM - Apothecary Patch.esp
	[FE:040] Dynamic Weather And Time Based Detection.esp
	[FE:041] [xPatch] Modpocalypse NPCs (v3) SSE - Immersive Encounters.esp
	[FE:042] [xPatch] Modpocalypse NPCs (v3) SSE - Weapons Armor Clothing & Clutter Fixes.esp
	[FE:043] BetterQuestObjectives.esp
	[FE:044] How Hard Is This Persuasion Check.esp
	[FE:045] Ryn's Dragon Mounds AIO.esp
	[FE:046] Hothtrooper44_ArmorCompilation_WACCF_Patch.esp
	[FE:047] ogCannibalDraugr.esp
	[FE:048] COTN Falkreath - ESO Imports patch.esp
	[FE:049] PrvtI_HeavyArmory_WACCF_Patch.esp
	[FE:04A] Prvti_ElvenSteel.esp
	[FE:04B] PrvtI_ElvenSteel_HA_WACCF_Patch.esp
	[FE:04C] PrvtI_HeavyArmory_USSEP.esp
	[FE:04D] PrvtI_HeavyArmory_WACCF_ISC.esp
	[FE:04E] LunarArmory_HA_WACCF_Patch.esp
	[FE:04F] Prvti_LunarArmory_HA_AddOn.esp
	[FE:050] Dawnguard - Tweaks and Enhancements.esp
	[FE:051] kikoSquirrelsofSkyrim.esp
	[FE:052] EVGAT SIP.esp
	[FE:053] Qw_BeyondSkyrimBruma_USSEP Hotfix Patch.esp
	[FE:054] mpThievesNightOnTheTown.esp
	[FE:055] Immersive Weapons_WACCF_Patch.esp
	[FE:056] PrvtI_ElvenSteel_HA_Addon.esp
	[FE:057] nchardak waterfall fix.esp
	[FE:058] PrvtI_HeavyArmory_Lite.esp
	[FE:059] [xPatch] Modpocalypse NPCs (v3) SSE - Immersive Weapons.esp
	[FE:05A] Qw_WACCF_BSHeartland Patch.esp
	[FE:05B] BSHeartland - Unofficial Patch.esp
	[FE:05C] FlyingCrowsSSE.esp
	[FE:05D] AHZBetterDGEntranceSE - BSHeartland Patch.esp
	[FE:05E] ksws03.esp
	[FE:05F] RoM - WACCF Patch.esp
	[FE:060] Qw_WACCF_ISC Patch.esp
	[FE:061] USMP - WACCF - GDO patch.esp
	[FE:062] ZimsImmersiveArtifacts_WACCF_Patch.esp
	[FE:063] CC-Fishing_WACCF_Patch.esp
	[FE:064] HouseOfHorrorsQuestExpansion.esp
	[FE:065] WACCF_Survival Mode_Patch.esp
	[FE:066] ApothecaryFood - Immersive World Encounters.esp
	[FE:067] 3BBB.esp
	[FE:068] McmRecorder.esp
	[FE:069] NW VAR Original Armor name patch.esp
	[FE:06A] NW VAR Qwinn WAACF BSHeartland Patch.esp
	[FE:06B] NW VAR Simply Faster Arrows Patch.esp
	[FE:06C] WACCF NW VAR Leftover Edits.esp
	[FE:06D] Landscape and Water Fixes - Patch - ELFX.esp
	[FE:06E] WindyGrass.esp
	[FE:06F] RoM - Saints & Seducers Patch.esp
	[FE:070] Bandit Lines Expansion for OBIS.esp
	[FE:071] DIS_Armor_Compilation_OBIS.esp
	[FE:072] DIS_Armor_Compilation_WACCF.esp
	[FE:073] Apothecary - WACCF.esp
	[FE:074] CompanionTweaks - USSEP.esp
	[FE:075] ISC USSEP Patch.esp
	[FE:076] UltimateDab.esp
	[FE:077] MVC Dark Dreams Vampire Clothes Replacer.esp
	[FE:078] dwPalmAndSoleOverlays-SE.esp
	[FE:079] Embers XD - Fire Magick Add-On.esp
	[FE:07A] MarkynazArmorPatch.esp
	[FE:07B] ImprovedLoadingScreenColors.esp
	[FE:07C] Immersive Armors - Asdasfa Tweaks and Fixes.esp
	[FE:07D] Maleficus' Blackjack.esp
