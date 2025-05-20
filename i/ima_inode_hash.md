# Function: <code>ima_inode_hash</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81532330)
Location: security/integrity/ima/ima_main.c:584
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff81532330-ffffffff8153234b: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153a7b0)
Location: security/integrity/ima/ima_main.c:585
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff8153a7b0-ffffffff8153a7cb: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81599150)
Location: security/integrity/ima/ima_main.c:602
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff81599150-ffffffff8159916b: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163dd20)
Location: security/integrity/ima/ima_main.c:625
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff8163dd20-ffffffff8163dd5b: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f5910)
Location: security/integrity/ima/ima_main.c:635
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff816f5910-ffffffff816f594b: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8172fb30)
Location: security/integrity/ima/ima_main.c:654
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff8172fb30-ffffffff8172fb6b: ima_inode_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_inode_hash(struct inode *inode, char *buf, size_t buf_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff817704c0)
Location: security/integrity/ima/ima_main.c:668
Inline: False
Direct callers:
  - kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash
```
**Symbols:**

```
ffffffff817704c0-ffffffff817704fb: ima_inode_hash (STB_GLOBAL)
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
