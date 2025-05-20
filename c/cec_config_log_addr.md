# Function: <code>cec_config_log_addr</code>

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
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81805e40)
Location: drivers/media/cec/cec-adap.c:1182
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81805e40-ffffffff81805f5e: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81847a30)
Location: drivers/media/cec/cec-adap.c:1227
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81847a30-ffffffff81847b56: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818792f0)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff818792f0-ffffffff81879416: cec_config_log_addr (STB_LOCAL)
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
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac0df0)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffff800010ac0df0-ffff800010ac0f30: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba2be8)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c0ba2be8-c0ba2d2c: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba3110)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
c000000000ba3110-c000000000ba32fc: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c23cc)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffe0006c23cc-ffffffe0006c24c4: cec_config_log_addr (STB_LOCAL)
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
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81821860)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81821860-ffffffff81821986: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e8f00)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff817e8f00-ffffffff817e9026: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186e7a0)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff8186e7a0-ffffffff8186e8c6: cec_config_log_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cec_config_log_addr(struct cec_adapter *adap, unsigned int idx, unsigned int log_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81888720)
Location: drivers/media/cec/cec-adap.c:1241
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
```
**Symbols:**

```
ffffffff81888720-ffffffff81888846: cec_config_log_addr (STB_LOCAL)
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
