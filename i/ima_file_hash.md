# Function: <code>ima_file_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81515200)
Location: security/integrity/ima/ima_main.c:516
Inline: False
```
**Symbols:**

```
ffffffff81515200-ffffffff81515300: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81532310)
Location: security/integrity/ima/ima_main.c:557
Inline: False
```
**Symbols:**

```
ffffffff81532310-ffffffff8153232f: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153a790)
Location: security/integrity/ima/ima_main.c:558
Inline: False
```
**Symbols:**

```
ffffffff8153a790-ffffffff8153a7af: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81599130)
Location: security/integrity/ima/ima_main.c:575
Inline: False
```
**Symbols:**

```
ffffffff81599130-ffffffff8159914f: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163dcd0)
Location: security/integrity/ima/ima_main.c:598
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_file_hash
```
**Symbols:**

```
ffffffff8163dcd0-ffffffff8163dd13: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f58b0)
Location: security/integrity/ima/ima_main.c:608
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_file_hash
```
**Symbols:**

```
ffffffff816f58b0-ffffffff816f58f3: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8172fad0)
Location: security/integrity/ima/ima_main.c:627
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_file_hash
```
**Symbols:**

```
ffffffff8172fad0-ffffffff8172fb16: ima_file_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_file_hash(struct file *file, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81770460)
Location: security/integrity/ima/ima_main.c:641
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_file_hash
```
**Symbols:**

```
ffffffff81770460-ffffffff817704a6: ima_file_hash (STB_GLOBAL)
```
</details>
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
