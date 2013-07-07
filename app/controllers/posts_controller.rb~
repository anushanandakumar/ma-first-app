class PostsController < ApplicationController
  def new
@post=Post.new
end
def create 
p=Post.create(params[:post])
p.save
redirect_to root_url
def index
@posts=Post.all
end

  end
end
