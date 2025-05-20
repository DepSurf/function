# Function: <code>keyctl_pkey_params_get</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81407740)
Location: security/keys/keyctl_pkey.c:82
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff81407740-ffffffff81407879: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81434900)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff81434900-ffffffff81434a42: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8144e680)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff8144e680-ffffffff8144e7c2: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814a0780)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff814a0780-ffffffff814a0809: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814be150)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff814be150-ffffffff814be1d9: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814c3f00)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff814c3f00-ffffffff814c4023: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8151c8d0)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff8151c8d0-ffffffff8151c9f3: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff815afa70)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff815afa70-ffffffff815afbc8: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8165a290)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff8165a290-ffffffff8165a3e8: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81692b60)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff81692b60-ffffffff81692cc8: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff816cf130)
Location: security/keys/keyctl_pkey.c:78
Inline: False
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff816cf130-ffffffff816cf298: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffff800010538bd0)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffff800010538bd0-ffff800010538d84: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (c06ef68c)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
c06ef68c-c06ef81c: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (c000000000687b00)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
c000000000687b00-c000000000687d3c: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffe000397868)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffe000397868-ffffffe0003979b8: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81446c60)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff81446c60-ffffffff81446da2: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814376b0)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff814376b0-ffffffff814377f2: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81442d00)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff81442d00-ffffffff81442e42: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int keyctl_pkey_params_get(key_serial_t id, const char *_info, struct kernel_pkey_params *params);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8145a030)
Location: security/keys/keyctl_pkey.c:78
Inline: True
Direct callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
**Symbols:**

```
ffffffff8145a030-ffffffff8145a172: keyctl_pkey_params_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
