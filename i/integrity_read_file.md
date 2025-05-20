# Function: <code>integrity_read_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int integrity_read_file(const char *path, char **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81f99980)
Location: security/integrity/iint.c:209
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff81f99980-ffffffff81f99a47: integrity_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int integrity_read_file(const char *path, char **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff81fc46f7)
Location: security/integrity/iint.c:211
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff81fc46f7-ffffffff81fc47bc: integrity_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int integrity_read_file(const char *path, char **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff8200112e)
Location: security/integrity/iint.c:211
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff8200112e-ffffffff820011f3: integrity_read_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int integrity_read_file(const char *path, char **data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/iint.c (ffffffff820e496a)
Location: security/integrity/iint.c:211
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_load_x509
```
**Symbols:**

```
ffffffff820e496a-ffffffff820e4a31: integrity_read_file (STB_GLOBAL)
```
</details>
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
</ul>
