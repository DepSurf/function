# Function: <code>async_unregister_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a33d0)
Location: kernel/async.c:252
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810a33d0-ffffffff810a3421: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a6af0)
Location: kernel/async.c:252
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810a6af0-ffffffff810a6b44: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ac750)
Location: kernel/async.c:252
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810ac750-ffffffff810ac7a4: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810a9320)
Location: kernel/async.c:252
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810a9320-ffffffff810a9367: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810afbb0)
Location: kernel/async.c:256
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810afbb0-ffffffff810afbf7: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b6a10)
Location: kernel/async.c:256
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810b6a10-ffffffff810b6a57: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810bfca0)
Location: kernel/async.c:256
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:exit_scsi
```
**Symbols:**

```
ffffffff810bfca0-ffffffff810bfce7: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/async.c (0)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810c5e1b-ffffffff810c5e2e: async_unregister_domain.cold (STB_LOCAL)
ffffffff810c5dd0-ffffffff810c5e1b: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810ceeb0)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810ceeb0-ffffffff810ceef7: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d8d70)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810d8d70-ffffffff810d8dba: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d3f10)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810d3f10-ffffffff810d3f5a: async_unregister_domain (STB_GLOBAL)
```
</details>
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
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffff80001012e480)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffff80001012e480-ffff80001012e540: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c037e690)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
c037e690-c037e71c: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (c000000000177d80)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
c000000000177d80-c000000000177e58: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffe0000e2a10)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffe0000e2a10-ffffffe0000e2aa4: async_unregister_domain (STB_GLOBAL)
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
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c9230)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810c9230-ffffffff810c9277: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810b7a50)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810b7a50-ffffffff810b7a91: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810c8760)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810c8760-ffffffff810c87a7: async_unregister_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void async_unregister_domain(struct async_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/async.c (ffffffff810d0750)
Location: kernel/async.c:257
Inline: False
```
**Symbols:**

```
ffffffff810d0750-ffffffff810d078e: async_unregister_domain (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
