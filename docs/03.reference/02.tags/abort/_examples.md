	<cfloop from="1" to="10" index="x">
		
		<cfdump var="#x#" />

		<!--- stops loop with x variable dump --->
		<cfabort />	
		
	</cfloop>
