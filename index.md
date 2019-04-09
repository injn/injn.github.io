window.intercomSettings = {
  app_id: "foqd1y2i",
  name: "<%= current_user.name %>", // Full name
  email: "<%= current_user.email %>", // Email address
  created_at: "<%= current_user.created_at.to_i %>" // Signup Date
};
