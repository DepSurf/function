# Function: <code>bpf_verify_pkcs7_signature</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_verify_pkcs7_signature(struct bpf_dynptr_kern *data_ptr, struct bpf_dynptr_kern *sig_ptr, struct bpf_key *trusted_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1335
Inline: False
```
**Symbols:**

```
ffffffff8205ecb0-ffffffff8205ecc5: bpf_verify_pkcs7_signature.cold (STB_LOCAL)
ffffffff812a97d0-ffffffff812a9863: bpf_verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_verify_pkcs7_signature(struct bpf_dynptr_kern *data_ptr, struct bpf_dynptr_kern *sig_ptr, struct bpf_key *trusted_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1348
Inline: False
```
**Symbols:**

```
ffffffff820dd842-ffffffff820dd857: bpf_verify_pkcs7_signature.cold (STB_LOCAL)
ffffffff812cc040-ffffffff812cc0d3: bpf_verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_verify_pkcs7_signature(struct bpf_dynptr_kern *data_ptr, struct bpf_dynptr_kern *sig_ptr, struct bpf_key *trusted_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: kernel/trace/bpf_trace.c:1379
Inline: False
```
**Symbols:**

```
ffffffff821b966f-ffffffff821b9683: bpf_verify_pkcs7_signature.cold (STB_LOCAL)
ffffffff812e93c0-ffffffff812e9460: bpf_verify_pkcs7_signature (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
