# Matrix table for django-Class-Based-View


## Base Class-Based-View


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				パラメータ名
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
	</tbody>
</table>


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				メソッド名
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
			<th rowspan="17">
				Attributes
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


## Detail Class-Based-View

<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				パラメータ名
			</th>
			<th>
				BaseDetailView
			</th>
			<th>
				DetailView
			</th>
			<th>
				SingleObjectMinxin
			</th>
			<th>
				SingleObjectTemplateResponseMixin
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="15">
				Attributes
			</th>
			<td>
				content_type 
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
				●
			</td>
		</tr>
		<tr>
			<td>
				context_object_name
			</td>
			<td>
				-
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
		</tr>
		<tr>
			<td>
				extra_context
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
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				model
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
		</tr>
		<tr>
			<td>
				pk_url_kwarg
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
		</tr>
		<tr>
			<td>
				query_pk_and_slug
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
		</tr>
		<tr>
			<td>
				queryset
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
		</tr>
		<tr>
			<td>
				slug_field
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
		</tr>
		<tr>
			<td>
				slug_url_kwarg
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
		</tr>
		<tr>
			<td>
				response_class
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_engine
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name_field
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name_suffix
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
				●
			</td>
		</tr>
	</tbody>
</table>


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				メソッド名
			</th>
			<th>
				BaseDetailView
			</th>
			<th>
				DetailView
			</th>
			<th>
				SingleObjectMinxin
			</th>
			<th>
				SingleObjectTemplateResponseMixin
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="15">
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
				●
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
				get_context_object_name
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
		</tr>
		<tr>
			<td>
				get_object
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
		</tr>
		<tr>
			<td>
				get_queryset
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
		</tr>
		<tr>
			<td>
				get_slug_field
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
				-
			</td>
			<td>
				-
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
				-
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
				-
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
		</tr>
		<tr>
			<td>
				render_to_response
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
				●
			</td>
		</tr>
	</tbody>
</table>

## Edit Class-Based-View


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				パラメータ名
			</th>
			<th>
				DeletionMixin
			</th>
			<th>
				FormMixin
			</th>
			<th>
				FormView
			</th>
			<th>
				 ModelFormMixin
			</th>
			<th>
				ProcessFormView
			</th>
			<th>
				UpdateView
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="20">
				Attributes
			</th>
			<td>
				content_type
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				context_object_name
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
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				fields
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				form_class
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				http_method_names
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				initial
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
				●
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
				model
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				pk_url_kwarg
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				prefix
			</td>
			<td>
				-
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				query_pk_and_slug
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				queryset
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				slug_field
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				slug_url_kwarg
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				success_url
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
				●
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
				response_class
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				template_engine
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name_field
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
				template_name_suffix
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
				-
			</td>
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
	</tbody>
</table>


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				メソッド名
			</th>
			<th>
				DeletionMixin
			</th>
			<th>
				FormMixin
			</th>
			<th>
				FormView
			</th>
			<th>
				 ModelFormMixin
			</th>
			<th>
				ProcessFormView
			</th>
			<th>
				UpdateView
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="26">
				Method
			</th>
			<td>
				_allowed_methods
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				as_view
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				delete
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				form_invalid
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				form_valid
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_context_data
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_context_object_name
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_form
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_form_class
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_form_kwargs
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_initial
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_object
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_prefix
			</td>
			<td>
				-
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
				●
			</td>
		</tr>
		<tr>
			<td>
				get_queryset
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_slug_field
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
			<td>
				-
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_success_url
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				get_template_names
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
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				http_method_not_allowd
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				__init__
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				options
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				post
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
				●
			</td>
			<td>
				●
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
				●
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
				●
			</td>
			<td>
				●
			</td>
		</tr>
		<tr>
			<td>
				render_to_response
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
			<td>
				●
			</td>
		</tr>
	</tbody>
</table>


## List Class-Based-View

<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				パラメータ名
			</th>
			<th>
				BaseListView
			</th>
			<th>
				ListView
			</th>
			<th>
				MultipleObjectMixin
			</th>
			<th>
				MultipleObjectTemplateResponseMixin
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="16">
				Attributes
			</th>
			<td>
				allow_empty
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
		</tr>
		<tr>
			<td>
				content_type
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
				●
			</td>
		</tr>
		<tr>
			<td>
				context_object_name
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
		</tr>
		<tr>
			<td>
				extra_context
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
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				ordering
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
		</tr>
		<tr>
			<td>
				page_kwarg
			</td>
			<td>
				-
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
		</tr>
		<tr>
			<td>
				paginate_by
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
		</tr>
		<tr>
			<td>
				paginate_orphans
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
		</tr>
		<tr>
			<td>
				paginator_class
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
		</tr>
		<tr>
			<td>
				queryset
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
		</tr>
		<tr>
			<td>
				model
			</td>
			<td>
				-
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
		</tr>
		<tr>
			<td>
				response_class
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_engine
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name
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
				●
			</td>
		</tr>
		<tr>
			<td>
				template_name_suffix
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
				●
			</td>
		</tr>
	</tbody>
</table>


<table>
	<thead>
		<tr>
			<th>
				種類
			</th>
			<th>
				メソッド名
			</th>
			<th>
				BaseListView
			</th>
			<th>
				ListView
			</th>
			<th>
				MultipleObjectMixin
			</th>
			<th>
				MultipleObjectTemplateResponseMixin
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th rowspan="19">
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
				get_allow_empty
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
		</tr>
		<tr>
			<td>
				get_context_data
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
		</tr>
		<tr>
			<td>
				get_context_object_name
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
		</tr>
		<tr>
			<td>
				get_ordering
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
		</tr>
		<tr>
			<td>
				get_paginate_by
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
		</tr>
		<tr>
			<td>
				get_paginate_orphans
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
		</tr>
		<tr>
			<td>
				get_paginator
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
		</tr>
		<tr>
			<td>
				get_queryset
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
		</tr>
		<tr>
			<td>
				get_template_names
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
				http_method_not_allowed
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
				-
			</td>
			<td>
				-
			</td>
		</tr>
		<tr>
			<td>
				option
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
				paginate_queryset
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
				-
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
		</tr>
	</tbody>
</table>