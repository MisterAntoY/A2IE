# Graph Report - A2IE  (2026-10-28)

## Corpus Check
- 106 files · ~41,295 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 5 file(s) not represented in the graph (top: (none) 2, .css 2, .tsbuildinfo 1)

## Summary
- 946 nodes · 2008 edges · 64 communities (41 shown, 23 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 15 edges (avg confidence: 0.89)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `5a6f8f59`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- react
- toast.tsx
- cn
- sidebar.tsx
- carousel.tsx
- utils.ts
- dependencies
- package.json
- field.tsx
- schemas.ts
- storage.ts
- BUG_REPORT.md
- command.tsx
- format_conf(1).ts
- compilerOptions
- components.json
- types.ts
- dropdown-menu.tsx
- class-variance-authority
- form.tsx
- menubar.tsx
- devDependencies
- context-menu.tsx
- store_conf(1).tsx
- TECHNICAL_DEBT.md
- PROJECT_ANALYSIS.md
- schemas_conf(1).ts
- export_conf(1).ts
- SECURITY_REVIEW.md
- item.tsx
- chart.tsx
- drawer.tsx
- select.tsx
- IMPROVEMENTS.md
- navigation-menu.tsx
- FEATURES_ROADMAP.md
- 3. Análise por categoria
- layout.tsx
- empty.tsx
- next-themes
- collapsible.tsx
- clsx
- popover.tsx
- scripts
- @radix-ui/react-aspect-ratio
- hover-card.tsx
- scroll-area.tsx
- next.config.mjs
- postcss.config.mjs
- cmdk
- date-fns@4.1.0
- next
- @radix-ui/react-alert-dialog
- @radix-ui/react-dialog
- @radix-ui/react-navigation-menu
- @radix-ui/react-progress
- @radix-ui/react-radio-group
- @radix-ui/react-select
- @radix-ui/react-slot
- @radix-ui/react-toggle-group
- react-dom@^19
- react-resizable-panels

## God Nodes (most connected - your core abstractions)
1. `cn()` - 277 edges
2. `react` - 68 edges
3. `useApp()` - 32 edges
4. `lucide-react` - 32 edges
5. `ReportsView()` - 20 edges
6. `compilerOptions` - 16 edges
7. `AppShell()` - 15 edges
8. `class-variance-authority` - 15 edges
9. `Dashboard()` - 14 edges
10. `Modal()` - 14 edges

## Surprising Connections (you probably didn't know these)
- `4. Acessibilidade` --references--> `Modal()`  [INFERRED]
  IMPROVEMENTS.md → components/feature/Modal.tsx
- `3.3 Persistência — ⚠ `localStorage` em claro` --references--> `SettingsView()`  [INFERRED]
  SECURITY_REVIEW.md → components/feature/SettingsView.tsx
- `B-11 🟡 Sem possibilidade de editar transações` --references--> `TransactionForm()`  [INFERRED]
  BUG_REPORT.md → components/feature/TransactionForm.tsx
- `2. Funcionalidades novas` --references--> `TransactionForm()`  [INFERRED]
  IMPROVEMENTS.md → components/feature/TransactionForm.tsx
- `B-19 🟡 Modal sem *focus trap*` --references--> `Tab`  [INFERRED]
  BUG_REPORT.md → components/feature/AppShell.tsx

## Import Cycles
- None detected.

## Communities (64 total, 23 thin omitted)

### Community 0 - "react"
Cohesion: 0.05
Nodes (87): Page(), B-19 🟡 Modal sem *focus trap*, AccountForm(), AccountsView(), PRESET_COLORS, AppShell(), Tab, TABS (+79 more)

### Community 1 - "toast.tsx"
Cohesion: 0.06
Nodes (52): Toast, ToastAction, ToastActionElement, ToastClose, ToastDescription, ToastProps, ToastTitle, toastVariants (+44 more)

### Community 2 - "cn"
Cohesion: 0.07
Nodes (39): AccordionContent(), AccordionItem(), AccordionTrigger(), Avatar(), AvatarFallback(), AvatarImage(), BreadcrumbEllipsis(), BreadcrumbItem() (+31 more)

### Community 3 - "sidebar.tsx"
Cohesion: 0.07
Nodes (39): Sheet(), SheetContent(), SheetDescription(), SheetFooter(), SheetHeader(), SheetOverlay(), SheetPortal(), SheetTitle() (+31 more)

### Community 4 - "carousel.tsx"
Cohesion: 0.08
Nodes (33): AlertDialogAction(), AlertDialogCancel(), AlertDialogContent(), AlertDialogDescription(), AlertDialogFooter(), AlertDialogHeader(), AlertDialogOverlay(), AlertDialogPortal() (+25 more)

### Community 5 - "utils.ts"
Cohesion: 0.09
Nodes (18): Checkbox(), InputGroup(), InputGroupAddon(), inputGroupAddonVariants, InputGroupButton(), inputGroupButtonVariants, InputGroupInput(), InputGroupText() (+10 more)

### Community 6 - "dependencies"
Cohesion: 0.07
Nodes (29): dependencies, autoprefixer@^10.4.20, @hookform/resolvers@^3.9.1, lucide-react@^0.564.0, @radix-ui/react-accordion@1.2.12, @radix-ui/react-checkbox@1.3.3, @radix-ui/react-context-menu@2.2.16, @radix-ui/react-hover-card@1.1.15 (+21 more)

### Community 7 - "package.json"
Cohesion: 0.08
Nodes (23): embla-carousel-react@8.6.0, input-otp@1.4.2, @radix-ui/react-avatar@1.1.11, @radix-ui/react-menubar@1.1.16, @radix-ui/react-popover@1.1.15, @radix-ui/react-scroll-area@1.2.10, @radix-ui/react-slider@1.3.6, @radix-ui/react-toggle@1.1.10 (+15 more)

### Community 8 - "field.tsx"
Cohesion: 0.12
Nodes (19): ButtonGroup(), ButtonGroupSeparator(), ButtonGroupText(), buttonGroupVariants, Field(), FieldContent(), FieldDescription(), FieldError() (+11 more)

### Community 9 - "schemas.ts"
Cohesion: 0.12
Nodes (20): GoalSchema, HexColorSchema, ISODateSchema, RecurrenceSchema, safeString(), sanitizeString(), TransactionKindSchema, TransactionSchema (+12 more)

### Community 10 - "storage.ts"
Cohesion: 0.15
Nodes (17): AccountSchema, BudgetSchema, CategorySchema, SettingsSchema, StateSchema, DEFAULT_ACCOUNTS, DEFAULT_EXPENSE_CATEGORIES, DEFAULT_INCOME_CATEGORIES (+9 more)

### Community 11 - "BUG_REPORT.md"
Cohesion: 0.10
Nodes (20): B-01 🔴 Data "TODAY" hardcoded como string, B-02 🔴 Mês selecionado hardcoded ao arrancar, B-03 🟠 Parsing de datas com bug de *timezone*, B-04 🟠 Persistência sem validação de *schema*, B-05 🟠 `JSON.parse` engole erros silenciosamente, B-06 🟠 ID baseado em `Date.now()` pode colidir, B-07 🟡 `parseFloat` aceita strings com lixo, B-08 🟡 *Daily average* mente quando há vários gastos no mesmo dia (+12 more)

### Community 12 - "command.tsx"
Cohesion: 0.16
Nodes (16): Command(), CommandDialog(), CommandGroup(), CommandInput(), CommandItem(), CommandList(), CommandSeparator(), CommandShortcut() (+8 more)

### Community 13 - "format_conf(1).ts"
Cohesion: 0.12
Nodes (7): formatDate(), formatDateShort(), formatISODate(), MONTH_NAMES_PT, parseISODate(), periodOf(), today()

### Community 14 - "compilerOptions"
Cohesion: 0.11
Nodes (18): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+10 more)

### Community 15 - "components.json"
Cohesion: 0.11
Nodes (17): aliases, components, hooks, lib, ui, utils, iconLibrary, rsc (+9 more)

### Community 16 - "types.ts"
Cohesion: 0.22
Nodes (16): Props, PrintReport, PrintReport, DEFAULT_ACCOUNTS, DEFAULT_EXPENSE_CATEGORIES, DEFAULT_INCOME_CATEGORIES, INITIAL_STATE, AppContextValue (+8 more)

### Community 17 - "dropdown-menu.tsx"
Cohesion: 0.11
Nodes (11): DropdownMenuCheckboxItem(), DropdownMenuContent(), DropdownMenuItem(), DropdownMenuLabel(), DropdownMenuRadioItem(), DropdownMenuSeparator(), DropdownMenuShortcut(), DropdownMenuSubContent() (+3 more)

### Community 18 - "class-variance-authority"
Cohesion: 0.16
Nodes (13): Alert(), AlertDescription(), AlertTitle(), alertVariants, Badge(), badgeVariants, ToggleGroup(), ToggleGroupContext (+5 more)

### Community 19 - "form.tsx"
Cohesion: 0.17
Nodes (14): FieldLabel(), FormControl(), FormDescription(), FormFieldContext, FormFieldContextValue, FormItem(), FormItemContext, FormItemContextValue (+6 more)

### Community 20 - "menubar.tsx"
Cohesion: 0.12
Nodes (12): Menubar(), MenubarCheckboxItem(), MenubarContent(), MenubarItem(), MenubarLabel(), MenubarPortal(), MenubarRadioItem(), MenubarSeparator() (+4 more)

### Community 21 - "devDependencies"
Cohesion: 0.12
Nodes (17): devDependencies, postcss@^8.5, tailwindcss@^4.2.0, @tailwindcss/postcss@^4.2.0, tw-animate-css@1.3.3, @types/node@^22, @types/react@^19, @types/react-dom@^19 (+9 more)

### Community 22 - "context-menu.tsx"
Cohesion: 0.12
Nodes (9): ContextMenuCheckboxItem(), ContextMenuContent(), ContextMenuItem(), ContextMenuLabel(), ContextMenuRadioItem(), ContextMenuSeparator(), ContextMenuShortcut(), ContextMenuSubContent() (+1 more)

### Community 23 - "store_conf(1).tsx"
Cohesion: 0.20
Nodes (15): clearState(), loadState(), pick(), recoverPartial(), saveState(), Action, AppContext, AppProvider() (+7 more)

### Community 24 - "TECHNICAL_DEBT.md"
Cohesion: 0.12
Nodes (15): Sumário priorizado, TD-01 — Sem testes automatizados, TD-02 — Componentes `shadcn/ui` por usar, TD-03 — Persistência em `localStorage`, TD-04 — Sem virtualização da lista, TD-05 — Sem ESLint / Prettier configurados, TD-06 — Sem CI/CD, TD-07 — Tema próprio em vez de `next-themes` (+7 more)

### Community 25 - "PROJECT_ANALYSIS.md"
Cohesion: 0.13
Nodes (14): 1.1 Stack identificada, 1.2 Estrutura encontrada (antes), 1. Visão geral, 2.1 Problemas estruturais identificados, 2.2 Acoplamento e duplicação, 2. Análise de arquitetura, 3.1 Pontos positivos do código original, 3.2 Pontos negativos (+6 more)

### Community 26 - "schemas_conf(1).ts"
Cohesion: 0.15
Nodes (13): AccountSchema, BudgetSchema, CategorySchema, GoalSchema, HexColorSchema, ISODateSchema, RecurrenceSchema, safeString() (+5 more)

### Community 27 - "export_conf(1).ts"
Cohesion: 0.27
Nodes (11): csvEscape(), download(), exportCSV(), exportJSON(), exportXLSX(), fmtMoney(), openPrintReport(), transactionsToCSV() (+3 more)

### Community 28 - "SECURITY_REVIEW.md"
Cohesion: 0.18
Nodes (5): 1. Modelo de ameaça, 2. Sumário do estado de segurança, 4. Recomendações ordenadas, 5. Checklist OWASP Top 10 (2021), 6. Conclusão

### Community 29 - "item.tsx"
Cohesion: 0.20
Nodes (11): Item(), ItemActions(), ItemContent(), ItemDescription(), ItemFooter(), ItemGroup(), ItemHeader(), ItemMedia() (+3 more)

### Community 30 - "chart.tsx"
Cohesion: 0.27
Nodes (10): ChartConfig, ChartContainer(), ChartContext, ChartContextProps, ChartLegendContent(), ChartStyle(), ChartTooltipContent(), getPayloadConfigFromPayload() (+2 more)

### Community 31 - "drawer.tsx"
Cohesion: 0.22
Nodes (7): DrawerContent(), DrawerDescription(), DrawerFooter(), DrawerHeader(), DrawerOverlay(), DrawerPortal(), DrawerTitle()

### Community 32 - "select.tsx"
Cohesion: 0.22
Nodes (7): SelectContent(), SelectItem(), SelectLabel(), SelectScrollDownButton(), SelectScrollUpButton(), SelectSeparator(), SelectTrigger()

### Community 33 - "IMPROVEMENTS.md"
Cohesion: 0.18
Nodes (10): 1.1 Separação em camadas, 1.2 Estado global (Context + Reducer), 1.3 Tipos discriminantes, 1. Arquitetura, 2. Funcionalidades novas, 3. UX / UI, 4. Acessibilidade, 5. Qualidade de código (+2 more)

### Community 34 - "navigation-menu.tsx"
Cohesion: 0.24
Nodes (9): NavigationMenu(), NavigationMenuContent(), NavigationMenuIndicator(), NavigationMenuItem(), NavigationMenuLink(), NavigationMenuList(), NavigationMenuTrigger(), navigationMenuTriggerStyle (+1 more)

### Community 35 - "FEATURES_ROADMAP.md"
Cohesion: 0.20
Nodes (9): Princípios de produto, v1.1 — Próximo incremento (pequenas melhorias), v1.2 — Internacionalização, v2.0 — Persistência multi-dispositivo, v2.1 — Inteligência, v2.2 — Importação inteligente, v3.0 — Mobile nativo, v3.1 — Investimentos & património (+1 more)

### Community 36 - "3. Análise por categoria"
Cohesion: 0.20
Nodes (10): 3.1 Cross-Site Scripting (XSS) — ✅ Mitigado, 3.2 Validação de entrada — ✅ Forte, 3.3 Persistência — ⚠ `localStorage` em claro, 3.4 Cabeçalhos HTTP — ⚠ Não configurados, 3.5 Dependências — ⚠ Sem auditoria automática, 3.6 Import / Export — ✅ Validado, 3.7 PDF / Print — ✅ Sem risco, 3.8 Exposição de PII em logs — ✅ Mitigado (+2 more)

### Community 37 - "layout.tsx"
Cohesion: 0.25
Nodes (7): geistMono, geistSans, metadata, RootLayout(), viewport, AppProvider(), reducer()

### Community 38 - "empty.tsx"
Cohesion: 0.29
Nodes (7): Empty(), EmptyContent(), EmptyDescription(), EmptyHeader(), EmptyMedia(), emptyMediaVariants, EmptyTitle()

### Community 41 - "clsx"
Cohesion: 0.33
Nodes (4): clsx@^2.1.1, tailwind-merge@^3.3.1, clsx, tailwind-merge

### Community 43 - "scripts"
Cohesion: 0.40
Nodes (5): scripts, build, dev, lint, start

## Knowledge Gaps
- **23 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `react` connect `react` to `toast.tsx`, `cn`, `sidebar.tsx`, `carousel.tsx`, `utils.ts`, `dependencies`, `package.json`, `field.tsx`, `command.tsx`, `dropdown-menu.tsx`, `class-variance-authority`, `form.tsx`, `menubar.tsx`, `context-menu.tsx`, `store_conf(1).tsx`, `item.tsx`, `chart.tsx`, `drawer.tsx`, `select.tsx`, `navigation-menu.tsx`, `next-themes`, `popover.tsx`, `hover-card.tsx`, `scroll-area.tsx`?**
  _High betweenness centrality (0.369) - this node is a cross-community bridge._
- **Should `react` be split into smaller, more focused modules?**
  _Cohesion score 0.051274747187010396 - nodes in this community are weakly interconnected._
- **Why does `cn()` connect `cn` to `toast.tsx`, `sidebar.tsx`, `carousel.tsx`, `utils.ts`, `field.tsx`, `command.tsx`, `dropdown-menu.tsx`, `class-variance-authority`, `form.tsx`, `menubar.tsx`, `context-menu.tsx`, `item.tsx`, `chart.tsx`, `drawer.tsx`, `select.tsx`, `navigation-menu.tsx`, `empty.tsx`, `popover.tsx`, `hover-card.tsx`, `scroll-area.tsx`?**
  _High betweenness centrality (0.200) - this node is a cross-community bridge._
- **Should `toast.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.05747126436781609 - nodes in this community are weakly interconnected._
- **Why does `lucide-react` connect `react` to `select.tsx`, `toast.tsx`, `cn`, `navigation-menu.tsx`, `carousel.tsx`, `utils.ts`, `sidebar.tsx`, `package.json`, `dependencies`, `command.tsx`, `dropdown-menu.tsx`, `menubar.tsx`, `context-menu.tsx`?**
  _High betweenness centrality (0.092) - this node is a cross-community bridge._
- **Should `cn` be split into smaller, more focused modules?**
  _Cohesion score 0.06901960784313725 - nodes in this community are weakly interconnected._
- **Should `sidebar.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.07246376811594203 - nodes in this community are weakly interconnected._