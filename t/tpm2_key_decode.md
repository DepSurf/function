# Function: <code>tpm2_key_decode</code>

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
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c6990)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff814c6990-ffffffff814c6a75: tpm2_key_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151f470)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff8151f470-ffffffff8151f555: tpm2_key_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b2ad0)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff815b2ad0-ffffffff815b2bc1: tpm2_key_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165d720)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff8165d720-ffffffff8165d811: tpm2_key_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696040)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff81696040-ffffffff8169615d: tpm2_key_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_key_decode(struct trusted_key_payload *payload, struct trusted_key_options *options, u8 **buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2690)
Location: security/keys/trusted-keys/trusted_tpm2.c:96
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
```
**Symbols:**

```
ffffffff816d2690-ffffffff816d27ad: tpm2_key_decode (STB_LOCAL)
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
