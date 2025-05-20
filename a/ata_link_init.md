# Function: <code>ata_link_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cf1c0)
Location: drivers/ata/libata-core.c:5559
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff815cf1c0-ffffffff815cf28d: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81627da0)
Location: drivers/ata/libata-core.c:5751
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81627da0-ffffffff81627e5f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81658a00)
Location: drivers/ata/libata-core.c:5793
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81658a00-ffffffff81658acd: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166d200)
Location: drivers/ata/libata-core.c:5879
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8166d200-ffffffff8166d2bf: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d6850)
Location: drivers/ata/libata-core.c:5910
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff816d6850-ffffffff816d690f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81712490)
Location: drivers/ata/libata-core.c:5926
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81712490-ffffffff8171254f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81734930)
Location: drivers/ata/libata-core.c:5930
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81734930-ffffffff817349fd: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817702c0)
Location: drivers/ata/libata-core.c:5915
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817702c0-ffffffff8177037f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794320)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81794320-ffffffff817943df: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81858650)
Location: drivers/ata/libata-core.c:5180
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81858650-ffffffff8185870f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818688b0)
Location: drivers/ata/libata-core.c:5180
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff818688b0-ffffffff8186896f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8184b220)
Location: drivers/ata/libata-core.c:5180
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff8184b220-ffffffff8184b2df: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d8630)
Location: drivers/ata/libata-core.c:5240
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff818d8630-ffffffff818d86ef: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a29830)
Location: drivers/ata/libata-core.c:5223
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81a29830-ffffffff81a2990e: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bac350)
Location: drivers/ata/libata-core.c:5229
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81bac350-ffffffff81bac42e: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c034f0)
Location: drivers/ata/libata-core.c:5454
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81c034f0-ffffffff81c035bb: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c58cb0)
Location: drivers/ata/libata-core.c:5422
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-sata.c:ata_slave_link_init
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81c58cb0-ffffffff81c58d7b: ata_link_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099e960)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffff80001099e960-ffff80001099ea00: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6effc)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
c0a6effc-c0a6f088: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a62d00)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
c000000000a62d00-c000000000a62db4: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe8c6)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffe0005fe8c6-ffffffe0005fe966: ata_link_init (STB_GLOBAL)
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
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759430)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff81759430-ffffffff817594ef: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817392d0)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817392d0-ffffffff8173938f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817891a0)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817891a0-ffffffff8178925f: ata_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_link_init(struct ata_port *ap, struct ata_link *link, int pmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a2ff0)
Location: drivers/ata/libata-core.c:5939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_slave_link_init
  - drivers/ata/libata-core.c:ata_port_alloc
  - drivers/ata/libata-pmp.c:sata_pmp_attach
```
**Symbols:**

```
ffffffff817a2ff0-ffffffff817a30af: ata_link_init (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
