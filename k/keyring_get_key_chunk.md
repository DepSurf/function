# Function: <code>keyring_get_key_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81330de0)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff81330de0-ffffffff81330e8f: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81365b60)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff81365b60-ffffffff81365c0d: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137c380)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8137c380-ffffffff8137c42d: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8138fe40)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8138fe40-ffffffff8138fef0: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b5370)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff813b5370-ffffffff813b5420: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e5ba0)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff813e5ba0-ffffffff813e5c53: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400380)
Location: security/keys/keyring.c:230
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff81400380-ffffffff81400433: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142c680)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8142c680-ffffffff8142c70c: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814463d0)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff814463d0-ffffffff8144645c: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81498519)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff81497860-ffffffff814978fb: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b5f89)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff814b52d0-ffffffff814b536b: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bbe09)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff814bb180-ffffffff814bb20b: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81514669)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff815139b0-ffffffff81513a3b: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a6ca9)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff815a5e70-ffffffff815a5f37: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81650c59)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8164fcf0-ffffffff8164fdb7: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81689529)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff816885d0-ffffffff8168869b: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c5a09)
Location: security/keys/keyring.c:268
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff816c4a50-ffffffff816c4b1b: keyring_get_key_chunk (STB_LOCAL)
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
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff80001052f638)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffff80001052f638-ffff80001052f724: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e7888)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
c06e7888-c06e793c: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067c300)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
c00000000067c300-c00000000067c3f4: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000390d18)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffe000390d18-ffffffe000390de8: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143e9b0)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8143e9b0-ffffffff8143ea3c: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142f420)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8142f420-ffffffff8142f4ac: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143ab50)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff8143ab50-ffffffff8143abdc: keyring_get_key_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int keyring_get_key_chunk(const void *data, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81451ca0)
Location: security/keys/keyring.c:268
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_get_object_key_chunk
```
**Symbols:**

```
ffffffff81451ca0-ffffffff81451d2c: keyring_get_key_chunk (STB_LOCAL)
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
