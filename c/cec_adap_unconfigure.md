# Function: <code>cec_adap_unconfigure</code>

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
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81804910)
Location: drivers/media/cec/cec-adap.c:1258
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81804910-ffffffff818049b6: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1303
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81845f30-ffffffff81845ff3: cec_adap_unconfigure (STB_LOCAL)
ffffffff818488e6-ffffffff818488f9: cec_adap_unconfigure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877860)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81877860-ffffffff8187792a: cec_adap_unconfigure (STB_LOCAL)
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
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abf390)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffff800010abf390-ffff800010abf43c: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba1078)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c0ba1078-c0ba1134: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0dc0)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c000000000ba0dc0-c000000000ba0e8c: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0d24)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffe0006c0d24-ffffffe0006c0dae: cec_adap_unconfigure (STB_LOCAL)
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
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181fdd0)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff8181fdd0-ffffffff8181fe9a: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e7470)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff817e7470-ffffffff817e753a: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186cd10)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff8186cd10-ffffffff8186cdda: cec_adap_unconfigure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cec_adap_unconfigure(struct cec_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886ca0)
Location: drivers/media/cec/cec-adap.c:1317
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81886ca0-ffffffff81886d6a: cec_adap_unconfigure (STB_LOCAL)
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
