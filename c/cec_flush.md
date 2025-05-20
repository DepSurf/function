# Function: <code>cec_flush</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804410)
Location: drivers/media/cec/cec-adap.c:393
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff81804410-ffffffff818044c1: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845a70)
Location: drivers/media/cec/cec-adap.c:406
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff81845a70-ffffffff81845b1b: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877370)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff81877370-ffffffff81877440: cec_flush (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abed38)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffff800010abed38-ffff800010abee14: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba0a24)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
c0ba0a24-c0ba0b00: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0610)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
c000000000ba0610-c000000000ba0748: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c07ee)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffe0006c07ee-ffffffe0006c08ae: cec_flush (STB_LOCAL)
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
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181f8e0)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff8181f8e0-ffffffff8181f9b0: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6f80)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff817e6f80-ffffffff817e7050: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186c820)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff8186c820-ffffffff8186c8f0: cec_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_flush(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818867b0)
Location: drivers/media/cec/cec-adap.c:407
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_adap_unconfigure
  - drivers/media/cec/cec-adap.c:cec_thread_func
```
**Symbols:**

```
ffffffff818867b0-ffffffff81886880: cec_flush (STB_LOCAL)
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
