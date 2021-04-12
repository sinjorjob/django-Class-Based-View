# Matrix table for django-Class-Based-View


## Base Class-Based-View


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				パラメータ名/メソッド名
			</th>
			<th>
				TemplateView
			</th>
			<th>
				View
			</th>
			<th>
				RedirectView
			</th>
			<th>
				ContextMixin
			</th>
			<th>
				TemplateResponseMixin
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="10">
				Attributes
			</th>
			<td>
				content_type 
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				extra_context
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				http_method_names
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				response_class
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				template_engine
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				pattern_name
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				permanent
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				query_string
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				url
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<th rowspan="17">
				Method
			</th>
			<td>
				_allowed_methods
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				as_view
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				dispatch
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				get
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				get_context_data
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				get_template_names
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				http_method_not_allowd
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				__init__
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				options
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				render_to_response
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				setup
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				delete
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				get_redirect_url
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				head
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				patch
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				post
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				put
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
			<td>
				-
			</td>
			<td>
				-
			</td>
		</tr>
	</tbody>
</table>