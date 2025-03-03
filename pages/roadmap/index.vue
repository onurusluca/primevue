<template>
    <div>
        <Head>
            <Title>PrimeVue Roadmap</Title>
            <Meta name="description" content="PrimeVue Roadmap" />
        </Head>

        <div class="doc-intro">
            <h1>Roadmap</h1>
            <p>
                At <a href="https://www.primetek.com.tr/" class="font-medium hover:underline text-primary">PrimeTek</a>, we are passionate about improving PrimeVue and would like to share our ideas for 2023 with the community. These are planned to be
                implemented in parallel to the regular maintenance work of the library involving review of issue tickets, PRs and PrimeVue PRO support.
            </p>
        </div>

        <div class="overflow-auto">
            <div style="min-width: 1200px">
                <div class="flex gap-3 mb-3">
                    <div class="flex-shrink-0 w-14rem"></div>
                    <div class="flex-1 bg-bluegray-500 text-white font-bold text-center p-3 text-xl border-round">Q1</div>
                    <div class="flex-1 bg-bluegray-500 text-white font-bold text-center p-3 text-xl border-round">Q2</div>
                    <div class="flex-1 bg-bluegray-500 text-white font-bold text-center p-3 text-xl border-round">Q3</div>
                    <div class="flex-1 bg-bluegray-500 text-white font-bold text-center p-3 text-xl border-round">Q4</div>
                </div>
                <div class="flex flex-column gap-3">
                    <div class="flex gap-3 border-bottom-1 surface-border pb-3">
                        <div class="flex-shrink-0 p-3 bg-blue-500 text-white border-round font-bold text-lg flex align-items-center justify-content-center w-14rem">COMPONENTS</div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Accessibility</h2>
                                <p class="mt-0 mb-3 line-height-3">WCAG Level AA compliance for all components with screen reader and keyboard support based on community feedback and audit tools.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Pass Through Props</h2>
                                <p class="mt-0 mb-3 line-height-3">Initate the implementation of Pass Through Props to provide advanced control over component internals.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Unstyled Mode</h2>
                                <p class="mt-0 mb-3 line-height-3">Introduce new unstyled mode to fully support styling with CSS libraries like Tailwind.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Tailwind Theme</h2>
                                <p class="mt-0 mb-3 line-height-3">A built-in TailwindCSS theme using the new Unstyled mode.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">New Design Tokens</h2>
                                <p class="mt-0 mb-3 line-height-3">Introduce new design tokens for styled mode.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">CSS Variables</h2>
                                <p class="mt-0 mb-3 line-height-3">Implement design tokens as CSS variables instead of SCSS.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">New Styled Mode</h2>
                                <p class="mt-0 mb-3 line-height-3">Move theming into core to replace external sass repo.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-blue-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">RTL Mode</h2>
                                <p class="mt-0 mb-3 line-height-3">Begin RTL support.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-blue-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex gap-3 border-bottom-1 surface-border pb-3">
                        <div class="flex-shrink-0 p-3 bg-indigo-500 text-white border-round font-bold text-lg flex align-items-center justify-content-center w-14rem">Figma UI Kit</div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-indigo-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Tokens</h2>
                                <p class="mt-0 mb-3 line-height-3">Initiated support for Figma Tokens.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-indigo-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-indigo-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Tokens</h2>
                                <p class="mt-0 mb-3 line-height-3">Initial release of Figma Tokens.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-indigo-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-indigo-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Tokens</h2>
                                <p class="mt-0 mb-3 line-height-3">Sync new design tokens.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-indigo-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex gap-3 border-bottom-1 surface-border pb-3">
                        <div class="flex-shrink-0 p-3 bg-teal-500 text-white border-round font-bold text-lg flex align-items-center justify-content-center w-14rem">SHOWCASE</div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-teal-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Nuxt</h2>
                                <p class="mt-0 mb-3 line-height-3">Migrate showcase application to Nuxt for SSR.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-teal-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-teal-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Demos</h2>
                                <p class="mt-0 mb-3 line-height-3">Standalone demos for each component feature instead of one demo page that demonstrates multiple features.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-teal-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                            <div class="p-3 surface-card border-round border-teal-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Documentation</h2>
                                <p class="mt-0 mb-3 line-height-3">New component API docs generated by TSDoc.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-teal-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                    </div>
                    <div class="flex gap-3 border-bottom-1 surface-border pb-3">
                        <div class="flex-shrink-0 p-3 bg-orange-500 text-white border-round font-bold text-lg flex align-items-center justify-content-center w-14rem">PrimeBlocks</div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-orange-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Blocks Update</h2>
                                <p class="mt-0 mb-3 line-height-3">New UI Blocks.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-orange-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex gap-3 border-bottom-1 surface-border pb-3">
                        <div class="flex-shrink-0 p-3 bg-pink-500 text-white border-round font-bold text-lg flex align-items-center justify-content-center w-14rem">Designer</div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-pink-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">Open Source Designer</h2>
                                <p class="mt-0 mb-3 line-height-3">Open source the sass based theming api and the visual designer.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-pink-500 border-round" style="width: 100%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column"></div>
                        <div class="flex-1 flex gap-3 flex-column">
                            <div class="p-3 surface-card border-round border-pink-500" style="border-left: 6px solid">
                                <h2 class="text-lg font-bold mt-0 mb-2">New UI Based Theme Editor</h2>
                                <p class="mt-0 mb-3 line-height-3">Advanced Theme Editor with full control over the Theming API.</p>
                                <div class="surface-200 border-round">
                                    <div class="bg-pink-500 border-round" style="width: 0%; height: 4px"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
