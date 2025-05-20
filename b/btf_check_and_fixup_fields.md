# Function: <code>btf_check_and_fixup_fields</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_check_and_fixup_fields(const struct btf *btf, struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81315e30)
Location: kernel/bpf/btf.c:3722
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81315e30-ffffffff81315f1f: btf_check_and_fixup_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_check_and_fixup_fields(const struct btf *btf, struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81345df0)
Location: kernel/bpf/btf.c:3835
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81345df0-ffffffff81345ef2: btf_check_and_fixup_fields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_check_and_fixup_fields(const struct btf *btf, struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136c730)
Location: kernel/bpf/btf.c:3843
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8136c730-ffffffff8136c839: btf_check_and_fixup_fields (STB_GLOBAL)
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
