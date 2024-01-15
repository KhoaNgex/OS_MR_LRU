# Simple Operating System

## Moi truong
- `Ubuntu` 22.04 LTS

## Cac buoc chay chuong trinh
- B1: `make all`: bien dich toan bo ma nguon.
- B2: `./os [configure file]`: chay mo phong voi cac file trong folder input

## Cac loai file input
+ Chay dinh thoi: sched, sched_0, sched_1
- Truoc khi bien dich ma nguon, MO FILE include/os-cfg.h va ENABLE dong `#define MM_FIXED_MEMSZ`, DISABLE 2 dong `#define VMDBG 1` va `#define MMDBG 1`, sau do `make all`.
- chay: VD. `./os sched`

+ Chay phan trang: os_1_singleCPU_mlq_paging, os_1_mlq_paging_small_4K, os_1_mlq_paging,...
- Truoc khi bien dich ma nguon, MO FILE include/os-cfg.h va DISABLE dong `#define MM_FIXED_MEMSZ`, ENABLE 2 dong `#define VMDBG 1` va `#define MMDBG 1`, sau do `make all`.
- chay: VD. `./os os_1_mlq_paging`

## LUU Y:
- Neu khong DISABLE va ENABLE dung cac dong trong include/os-cfg.h thi CODE SE CHAY RA KHONG DUNG!






