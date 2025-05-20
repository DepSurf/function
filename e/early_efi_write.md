# Function: <code>early_efi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff81079e70)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff81079e70-ffffffff8107a108: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff8107b720)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff8107b720-ffffffff8107b9b9: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff8107fcc0)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff8107fcc0-ffffffff8107ff52: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff8107dfd0)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff8107dfd0-ffffffff8107e265: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff81084800)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff81084800-ffffffff81084a95: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff81087af0)
Location: arch/x86/platform/efi/early_printk.c:127
Inline: False
```
**Symbols:**

```
ffffffff81087af0-ffffffff81087d9a: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_efi_write(struct console *con, const char *str, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/early_printk.c (ffffffff8108f250)
Location: arch/x86/platform/efi/early_printk.c:131
Inline: False
```
**Symbols:**

```
ffffffff8108f250-ffffffff8108f4fe: early_efi_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
