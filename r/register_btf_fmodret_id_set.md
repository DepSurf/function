# Function: <code>register_btf_fmodret_id_set</code>

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
int register_btf_fmodret_id_set(const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313d40)
Location: kernel/bpf/btf.c:7664
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff81313d40-ffffffff81313d60: register_btf_fmodret_id_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_btf_fmodret_id_set(const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343b50)
Location: kernel/bpf/btf.c:7925
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff81343b50-ffffffff81343b70: register_btf_fmodret_id_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_btf_fmodret_id_set(const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369ae0)
Location: kernel/bpf/btf.c:7990
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
  - net/mptcp/bpf.c:bpf_mptcp_kfunc_init
```
**Symbols:**

```
ffffffff81369ae0-ffffffff81369b00: register_btf_fmodret_id_set (STB_GLOBAL)
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
