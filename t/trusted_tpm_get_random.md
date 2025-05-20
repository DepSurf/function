# Function: <code>trusted_tpm_get_random</code>

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
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c4a80)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff814c4a80-ffffffff814c4a9d: trusted_tpm_get_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d460)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff8151d460-ffffffff8151d47d: trusted_tpm_get_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b07e0)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff815b07e0-ffffffff815b0807: trusted_tpm_get_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b1b0)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff8165b1b0-ffffffff8165b1d7: trusted_tpm_get_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81693aa0)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff81693aa0-ffffffff81693ac7: trusted_tpm_get_random (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trusted_tpm_get_random(unsigned char *key, size_t key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d00a0)
Location: security/keys/trusted-keys/trusted_tpm1.c:976
Inline: False
```
**Symbols:**

```
ffffffff816d00a0-ffffffff816d00c7: trusted_tpm_get_random (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
