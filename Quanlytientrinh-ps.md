# Câu lệnh quản lý tiến trình

Khi 1 công việc được thực thi trong shell, một tiến trình sẽ được tạo ra và gán các định danh duy nhất (PID). Những tiến trình thể hiện qua lệnh `ps`

- Hiển thị tất các các tiến trình:

```sh
ps -A
```
hoặc 
```sh
ps -e
```

- Hiển thị tiến trình theo lệnh:

```sh
ps -C
```

- Hiển thị tiến trình theo chỉ số

```sh
ps -p
```

- 