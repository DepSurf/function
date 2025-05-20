# Function: <code>__selem_unlink_sk</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952b20)
Location: net/core/bpf_sk_storage.c:144
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff81952b20-ffffffff81952c1b: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988e70)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff81988e70-ffffffff81988f6b: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60b10)
Location: net/core/bpf_sk_storage.c:148
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff81a60b10-ffffffff81a60c0c: __selem_unlink_sk (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c315a0)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffff800010c315a0-ffff800010c316cc: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d47f48)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
c0d47f48-c0d48064: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a0f0)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
c000000000d2a0f0-c000000000d2a24c: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a6f94)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffe0007a6f94-ffffffe0007a7056: __selem_unlink_sk (STB_LOCAL)
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
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928ce0)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff81928ce0-ffffffff81928ddb: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2a90)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff818e2a90-ffffffff818e2b8b: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979e70)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff81979e70-ffffffff81979f6b: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __selem_unlink_sk(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_elem *selem, bool uncharge_omem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c3a0)
Location: net/core/bpf_sk_storage.c:147
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
**Symbols:**

```
ffffffff8199c3a0-ffffffff8199c49b: __selem_unlink_sk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
