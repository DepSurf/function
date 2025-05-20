# Function: <code>compress_zstd</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compress_zstd(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8161d150)
Location: security/apparmor/policy_unpack.c:1319
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8161d150-ffffffff8161d30d: compress_zstd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compress_zstd(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d04e0)
Location: security/apparmor/policy_unpack.c:1310
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff816d04e0-ffffffff816d06a6: compress_zstd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compress_zstd(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff817090c0)
Location: security/apparmor/policy_unpack.c:1339
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff817090c0-ffffffff81709298: compress_zstd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compress_zstd(const char *src, size_t slen, char **dst, size_t *dlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81746b50)
Location: security/apparmor/policy_unpack.c:1373
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff81746b50-ffffffff81746d28: compress_zstd (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
