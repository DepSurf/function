# Function: <code>security_read_state_kernel</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_read_state_kernel(struct selinux_state *state, void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1f40)
Location: security/selinux/ss/services.c:4034
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff814f1f40-ffffffff814f1fe5: security_read_state_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_read_state_kernel(struct selinux_state *state, void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8154c630)
Location: security/selinux/ss/services.c:4045
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff8154c630-ffffffff8154c6d5: security_read_state_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_read_state_kernel(struct selinux_state *state, void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e54f0)
Location: security/selinux/ss/services.c:4048
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff815e54f0-ffffffff815e55c2: security_read_state_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_read_state_kernel(struct selinux_state *state, void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81694970)
Location: security/selinux/ss/services.c:4041
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff81694970-ffffffff81694a42: security_read_state_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_read_state_kernel(void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816cce90)
Location: security/selinux/ss/services.c:3975
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff816cce90-ffffffff816ccf63: security_read_state_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_read_state_kernel(void **data, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81709470)
Location: security/selinux/ss/services.c:3994
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
```
**Symbols:**

```
ffffffff81709470-ffffffff81709543: security_read_state_kernel (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, data, len</code> ➡️ <code>data, len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
