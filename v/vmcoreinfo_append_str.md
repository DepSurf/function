# Function: <code>vmcoreinfo_append_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110d820)
Location: kernel/kexec_core.c:1327
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/kexec_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
```
**Symbols:**

```
ffffffff8110d820-ffffffff8110d8f4: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81115260)
Location: kernel/kexec_core.c:1374
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81115260-ffffffff81115331: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111c980)
Location: kernel/kexec_core.c:1376
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/printk/printk.c:log_buf_kexec_setup
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo_init
  - kernel/kexec_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8111c980-ffffffff8111ca51: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8111d0d0)
Location: kernel/crash_core.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8111d0d0-ffffffff8111d1b2: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811287c0)
Location: kernel/crash_core.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff811287c0-ffffffff811288a2: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8113688b-ffffffff81136897: vmcoreinfo_append_str.cold.2 (STB_LOCAL)
ffffffff81136750-ffffffff8113682b: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8114201b-ffffffff81142027: vmcoreinfo_append_str.cold.2 (STB_LOCAL)
ffffffff81141ee0-ffffffff81141fb1: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8114d3cb-ffffffff8114d3d7: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff8114d290-ffffffff8114d361: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8115909b-ffffffff811590a7: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81158f60-ffffffff81159031: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81169c6b-ffffffff81169c77: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81169b40-ffffffff81169c0d: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:add_build_id_vmcoreinfo
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81be4480-ffffffff81be448c: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81166290-ffffffff8116635d: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81bd63a1-ffffffff81bd63ad: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81167030-ffffffff811670fd: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81cb2bc9-ffffffff81cb2bd5: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff8118c7f0-ffffffff8118c8bd: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff81e639fb-ffffffff81e63a07: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff811bbca0-ffffffff811bbda3: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8205bfab-ffffffff8205bfbf: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff811fdb20-ffffffff811fdc6b: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff820da78a-ffffffff820da79e: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81212ca0-ffffffff81212deb: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:690
Inline: False
Direct callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff821b6335-ffffffff821b6349: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff8122ab00-ffffffff8122ac4b: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff8000101c8568)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo
  - arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo
  - arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo
  - arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffff8000101c8568-ffff8000101c8658: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c040f4c8)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
c040f4c8-c040f580: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c000000000230bd0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
c000000000230bd0-c000000000230cc0: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe000148446)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffe000148446-ffffffe0001484ce: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff811516bb-ffffffff811516c7: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81151580-ffffffff81151651: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8114499b-ffffffff811449a7: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff81144860-ffffffff81144931: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8114f56b-ffffffff8114f577: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff8114f430-ffffffff8114f501: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void vmcoreinfo_append_str(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/printk/printk.c:log_buf_vmcoreinfo_setup
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
```
**Symbols:**

```
ffffffff8115c38b-ffffffff8115c397: vmcoreinfo_append_str.cold (STB_LOCAL)
ffffffff8115c250-ffffffff8115c321: vmcoreinfo_append_str (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
