<template>
	<!-- App -->
	<div id="app">
		
		<!-- Statusbar -->
		<f7-statusbar></f7-statusbar>
		
		<!-- Main Views -->
		<f7-views>
			<f7-view id="main-view" navbar-through :dynamic-navbar="true" main>
				<!-- Navbar -->
				<f7-navbar>
					<f7-nav-center sliding>EIS Advisor</f7-nav-center>
				</f7-navbar>
				<!-- Pages -->
				<f7-pages>
					<f7-page>
                        <f7-tabs>
                          <f7-tab id="tab1" active>						
                              <f7-block-title>Welcome to my App</f7-block-title>
                                <f7-block inner>
                                    <p>Duis sed erat ac eros ultrices pharetra id ut tellus. Praesent rhoncus enim ornare ipsum aliquet ultricies. Pellentesque sodales erat quis elementum sagittis.</p>
                                </f7-block>
                                <f7-block-title>Navigation</f7-block-title>
                                <f7-list>
                                    <f7-list-item link="/about/" title="About"></f7-list-item>
                                    <f7-list-item link="/form/" title="Form"></f7-list-item>
                                    <f7-list-item link="/dynamic-route/blog/45/post/125/?foo=bar#about" title="Dynamic Route"></f7-list-item>
                                </f7-list>
                          </f7-tab>
                          <f7-tab id="tab2">
                              <f7-block-title>Search</f7-block-title>
                          </f7-tab>
                          <f7-tab id="tab3">
                              <f7-block-title>Settings</f7-block-title>
                          </f7-tab>
                          <f7-tab id="tab4">
                              <f7-block-title>About</f7-block-title>
                          </f7-tab>
                        </f7-tabs>

                        <f7-toolbar tabbar>
                          <f7-link tab-link="#tab1" class="active">Home</f7-link>
                          <f7-link tab-link="#tab2">Search</f7-link>
                          <f7-link tab-link="#tab3">Settings</f7-link>
                          <f7-link tab-link="#tab4">About</f7-link>
                        </f7-toolbar>
					</f7-page>
				</f7-pages>
			</f7-view>
		</f7-views>
	</div>
</template>

<script>
    export default {}

</script>
