# Function: <code>ima_post_load_data</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:795
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff81bf1be1-ffffffff81bf1bf7: ima_post_load_data.cold (STB_LOCAL)
ffffffff81533500-ffffffff81533525: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:809
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff81be3c03-ffffffff81be3c1a: ima_post_load_data.cold (STB_LOCAL)
ffffffff8153ba50-ffffffff8153ba70: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:826
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff81cd6e58-ffffffff81cd6e6f: ima_post_load_data.cold (STB_LOCAL)
ffffffff8159a4e0-ffffffff8159a500: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:849
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff81e8a078-ffffffff81e8a097: ima_post_load_data.cold (STB_LOCAL)
ffffffff8163f220-ffffffff8163f250: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6f60)
Location: security/integrity/ima/ima_main.c:859
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff816f6f60-ffffffff816f6fa2: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff817311e0)
Location: security/integrity/ima/ima_main.c:878
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff817311e0-ffffffff81731221: ima_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_post_load_data(char *buf, loff_t size, enum kernel_load_data_id load_id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771c40)
Location: security/integrity/ima/ima_main.c:892
Inline: False
Direct callers:
  - security/security.c:security_kernel_post_load_data
```
**Symbols:**

```
ffffffff81771c40-ffffffff81771c81: ima_post_load_data (STB_GLOBAL)
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
